![](.images/poster.png)

# Beep Sans
Beep a font name derived from [Habeep](https://www.habeep.org) was created to replace the `Aeonik` font used in `Habeep Design System`.
Beep Sans is a sans-serif typeface made for designers and developers, embodying modern principles of simplicity, minimalism, and speed. It is designed to be used in headers, body, logo, headlines, posters and other large display sizes.
Beep, inspired by the clean lines and geometric forms of the Inter typeface [Inter](https://rsms.me/work/inter/) and [GeistSans](https://vercel.com/font), offers a modern take on sans-serif design.

### Installation

```sh
npm install beepsans
```

### Using Font

`Beep` can be used as a local fonts with CSS, TailwindCSS, Vue, React, Svelte and other Javascript Frameworks not listed here. We currently support OpenTypeFormat(otf).Our next release will feature TrueTypeFormat(ttf) and Web Open Font Format(WOFF)

#### CSS

```CSS
:root {
 font-family: 'Beep', sans-serif;
}
```
#### TailwindCSS

`tailwind.config.js`:
```javascript
module.exports = {
  content: [],
  theme: {
    extend: {
      fontFamily: {
        beep: "Beep, sans-serif",
      },
    },
  },
  plugins: []
};
```
#### Vue Template

```javascript
<template>
  <h1 style="font-family: 'Beep', sans-serif;">Hello, Vue</h1>
</template>

```
`Note:` While the provided code snippet above allows you to set the `Beep` font family in a components, it's recommended to declare fonts in a centralized location for better organization and maintainability.  `See the Example Below`.

#### src/styles.css

```CSS
:root {
 font-family: 'Beep', sans-serif;
}
```
#### JSX Component

```javascript
import React from 'react';

function MyComponent() {
  return (
    <h1 style={{ fontFamily: 'BeepFont', sans-serif }}>Hello, World!</h1>
  );
}
export default MyComponent;`
```

### License
The Beep font family is free and open sourced under the [SIL Open Font License](./LICENSE.TXT).

### Download and Installation
The Beep font family is free to download. OpenTypeFormat is available for download. 

`[1]`Download the first release by clicking the link below. 
`[2]`Start the download process
`[3]`Unzip file and Install the font.
* [Download Beep OTF](https://github.com/ulims/beep-font/releases/tag/release)
