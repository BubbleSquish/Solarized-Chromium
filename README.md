# Solarized Chromium Enhancement
<p align="center">
    <img width="200" src="https://github.com/BubbleSquish/Solarized-Chromium/blob/main/Solarized%20Chromium.png" alt="Solarized Chromium Logo">
</p>

Since the introduction of the `--enable-force-dark` flag in Chrome v78 on October 22nd, 2019, the browser's capability to render dark themes has significantly improved. This feature forces dark mode on web content, enhancing the browsing experience in low-light environments and reducing eye strain.

Note: 
* Solarized `source code` is found at [altercation/solarized](https://github.com/altercation/solarized) rather than Ethan Schoonover's website, but his website explains the reason why it was made it and how it works, see: [CIELAB](https://en.wikipedia.org/wiki/CIELAB_color_space)

Goal:
* **Togglable and Automatic Solarized Themes**: Introducing a toolbar button to dynamically switch between Solarized Light and Solarized Dark themes without needing a browser restart (tested and proven with `--enable-force-dark`). This feature is perfect for those who prefer not to use Solarized Dark constantly but still find white webpages glaring and straining on the eyes. This is why the project is named "Solarized Chromium" rather than "Solarized Dark Chromium".

I've decided to leverage this functionality to implement the [Solarized Dark](https://ethanschoonover.com/solarized/) color scheme globally across all webpages. [Solarized](https://ethanschoonover.com/solarized/), created by Ethan Schoonover, is a meticulously designed color palette that offers both dark and light themes with optimal contrast and readability.

### The Problem with Traditional Methods

Previously, achieving a global [Solarized Dark](https://ethanschoonover.com/solarized/) theme required the use of custom CSS user styles or extensions. These methods often led to inconsistent results, such as broken layouts or conflicting styles that degraded the user experience. Managing individual styles for each site was inefficient and time-consuming.

### The Solution: Harnessing Chrome's Native Capabilities

By enabling `chrome://flags/#enable-force-dark` and activating "Dark Mode" in `chrome://settings/?search=dark`, we can utilize Chrome's native theme generation engine. This approach allows us to apply a consistent Solarized Dark color scheme across all web content without the drawbacks of external stylesheets or extensions.

### Technical Approach

- **Force Dark Mode Flag**: Activating this flag forces Chrome to invert light colors in web content to create a dark theme dynamically.
- **Dark Mode Setting**: Enabling dark mode in Chrome's settings complements the flag by adjusting the browser's UI elements to dark. Additionally, it prompts websites to switch to their dark theme if they recognize and support this user preference, although many sites do not, even if they have a dark theme mode. Enabling the site's native dark mode theme will significantly enhance the quality of the generated [Solarized Dark](https://ethanschoonover.com/solarized/) color palette.
- **Color Calibration**: By fine-tuning Chrome's theme generation algorithms, we can map the dynamic colors to match the [Solarized Dark](https://ethanschoonover.com/solarized/) palette accurately.

### Benefits

- **Consistency**: Achieve a uniform look and feel across all websites without manual intervention.
- **Performance**: Reduce the overhead introduced by third-party extensions and custom user styles.
- **Simplicity**: Eliminate the need for managing individual stylesheets or relying on external tools.

---

This project aims to create a seamless and efficient way to enjoy the [Solarized Dark](https://ethanschoonover.com/solarized/) theme universally in Chrome. By tapping into Chrome's advanced rendering capabilities, we can enhance both aesthetics and functionality.

Stay tuned for updates on [Solarized Chromium](https://github.com/BubbleSquish/Solarized-Chromium).

---

Pre-Concept/Pre-Development Stage Status

*In progress of loading the initial loading phase of conceptualizing the programmatic source and integration for enhanced holographics.*

---

Although the following developers had nothing to do with the creation or idea for my particular project, I am still using their code to create [Solarized Chromium](https://github.com/BubbleSquish/Solarized-Chromium).

# Credits/Copyrights

[Chromium](https://source.chromium.org/chromium) by [Google](https://about.google/):

<sub><sup>Copyright 2015 The Chromium Authors</sub></sup>

<sub><sup>Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:</sub></sup>

   * <sub><sup>Redistributions of source code must retain the above copyright
notice, this list of conditions and the following disclaimer.</sub></sup>

   * <sub><sup>Redistributions in binary form must reproduce the above
copyright notice, this list of conditions and the following disclaimer
in the documentation and/or other materials provided with the
distribution.</sub></sup>

   * <sub><sup>Neither the name of Google LLC nor the names of its
contributors may be used to endorse or promote products derived from
this software without specific prior written permission.</sub></sup>

<sub><sup>THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.</sub></sup>

---

[Solarized](https://ethanschoonover.com/solarized/) by [Ethan Schoonover](https://ethanschoonover.com/):

<sub><sup>Copyright (c) 2011 Ethan Schoonover</sub></sup>

<sub><sup>Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:</sub></sup>

<sub><sup>The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.</sub></sup>

<sub><sup>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.</sub></sup>
