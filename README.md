# ASCII Art Generator
The only web application allowing you generate professional ASCII art completely for free!
Transform text, images, and AI prompts into retro terminal-style art.

## What is ASCII Art Generator
**ASCII Art Generator** is a lightweight web application that bridges the gap between modern imagery and classic 80s computer aesthetics. Whether you're converting a photo, styling text with custom fonts, or generating a silhouette using AI, this tool makes the digital-to-analog transition seamless and fun.

## Installing / Getting started
1. Clone the repo
2. Run `npm install`
3. Start development server: `npm run dev`
4. Build for production: `npm run build`

You can try the app just visiting [ASCII Art Generator](https://asciiart-generator.netlify.app/) website.

**IMPORTNAT!** No external access tokens or API keys are required for the base version. The AI Prompt feature uses the _Pollinations.ai_ public API, which is pre-configured to work out of the box via the Anonymous CORS setting in the script.

## Developing and contributing
Anyone is free to contrubute to the application.

To start developing and adding new ASCII styles or filters:

```
git clone https://github.com/PavloICSA/ascii-art-generator.git
cd ascii-art-generator/
```

**No npm install required - pure Vanilla JS!**
You are free to:
- Modify Styles: Add new character maps in the createTextASCII function.
- Adjust Density: Change the asciiChars string in processImageToASCII to alter how light/dark values are interpreted.

## Tech Stack
This project uses **HTML5** and **CSS3** with native **ES6+ JavaScript** engine.
No build step (like Webpack or Babel) is required unless you plan to minify the code for production.

## Features
- Text-to-ASCII: 10+ custom fonts (Standard, Big, Doom, 3-D, Bubble, etc.) manually mapped for high precision.

- Image-to-ASCII: Uses HTML5 Canvas to process local image uploads and convert pixels to brightness-mapped characters.

- AI Prompting: Generates high-contrast silhouettes via AI and automatically converts them to ASCII.

- Real-time Feedback: Character counters with color-coding to help users stay within ideal terminal widths.

- Aspect Ratio Correction: Intelligent scaling (0.55 ratio) to prevent "stretched" art caused by vertical line spacing in text editors.


## Links
Repository: https://github.com/PavloICSA/ascii-art-generator/

Issue tracker: https://github.com/PavloICSA/ascii-art-generator/issues

## Related projects:

**Pollinations.ai:** The engine powering our AI prompts.

## Licensing
The code in this project is licensed under the MIT license.