# Solarized Chromium Enhancement

Since the introduction of the `--enable-force-dark` flag in Chrome v78 on October 22nd, 2019, the browser's capability to render dark themes has significantly improved. This feature forces dark mode on web content, enhancing the browsing experience in low-light environments and reducing eye strain.

I've decided to leverage this functionality to implement the [Solarized Dark](https://ethanschoonover.com/solarized/) color scheme globally across all webpages. Solarized, created by Ethan Schoonover, is a meticulously designed color palette that offers both dark and light themes with optimal contrast and readability.

### The Problem with Traditional Methods

Previously, achieving a global Solarized theme required the use of custom CSS user styles or extensions. These methods often led to inconsistent results, such as broken layouts or conflicting styles that degraded the user experience. Managing individual styles for each site was inefficient and time-consuming.

### The Solution: Harnessing Chrome's Native Capabilities

By enabling `chrome://flags/#enable-force-dark` and activating "Dark Mode" in `chrome://settings/?search=dark`, we can utilize Chrome's native theme generation engine. This approach allows us to apply a consistent Solarized Dark color scheme across all web content without the drawbacks of external stylesheets or extensions.

### Technical Approach

- **Force Dark Mode Flag**: Activating this flag forces Chrome to invert light colors in web content to create a dark theme dynamically.
- **Dark Mode Setting**: Enabling dark mode in Chrome's settings complements the flag by adjusting the browser's UI elements to dark.
- **Color Calibration**: By fine-tuning Chrome's theme generation algorithms, we can map the dynamic colors to match the Solarized palette accurately.

### Benefits

- **Consistency**: Achieve a uniform look and feel across all websites without manual intervention.
- **Performance**: Reduce the overhead introduced by third-party extensions and custom user styles.
- **Simplicity**: Eliminate the need for managing individual stylesheets or relying on external tools.

---

This project aims to create a seamless and efficient way to enjoy the Solarized Dark theme universally in Chrome. By tapping into Chrome's advanced rendering capabilities, we can enhance both aesthetics and functionality.

Stay tuned for updates on [Solarized Chromium](https://github.com/BubbleSquish/Solarized-Chromium).

# Concept/Development Stage
In progress of loading the initial loading phase of conceptualizing the programmatic source and integration for enhanced holographics.
