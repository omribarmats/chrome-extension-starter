# Chrome Extension Starter with Vite, React, TypeScript, and Tailwind CSS
This project is a starter template for building modern Chrome extensions using Vite, React, TypeScript, and Tailwind CSS. It simplifies the setup so you can focus on building your extension's features.

<div style="display: flex; justify-content: space-around">
  <img src="https://github.com/user-attachments/assets/b2267b19-1618-4797-8e0e-a241697b92cf" alt="image 1" width="200"/>
  <img src="https://github.com/user-attachments/assets/eb6304c9-afd7-4bfc-b9ce-8099531a66d9" alt="image 2" width="200"/>
  <img src="https://github.com/user-attachments/assets/7808d29d-d1ca-4287-b82b-183ad7b6510a" alt="image 3" width="200"/>
  <img src="https://github.com/user-attachments/assets/c2f328e2-f7d6-4e6d-a3ec-8e750625e0f8" alt="image 4" width="200"/>
</div>



## Features
- **Fast reloading** develop UI faster, view the popup and options page
- **Vite** for fast bundling and development
- **React** for building interactive UI components
- **TypeScript** for type-safe JavaScript development
- **Tailwind CSS** for easy and responsive styling
- **Chrome Extension API** integrated for easy feature development

## Installation

### Clone this repository:
```
git clone https://github.com/omribarmats/chrome-extension-starter.git new-project
```
* Replace `new-project` with your project name

### Open the new directory:
```
cd new-project
```
### Install dependencies:
```
npm install
```
### Start the development server:
```
npm run dev
```
## Load the Extension

1. Run the build command: `npm run build.`
2. Go to `chrome://extensions/` in your Chrome browser.
3. Enable `Developer mode`.
4. Click `Load unpacked` and select the `dist` folder from the project.

## Development
- Hot-reload enabled for easier development.
- Modify your code in the src folder.
- Tailwind CSS is already configured and ready to use.
- Run `nmp run build` to implement changes to `dist` folder
- Go on `chrome://extensions/` and click refresh `⟳`

### How to change the popup? 
- Go on `src/chrome-extension/popup/index.tsx`
- Once changes are done run `nmp run build` and then visit your project on `chrome://extensions/` and click refresh `⟳`

### How to change the options page? 
- Go on `src/chrome-extension/options/index.tsx`
- Once changes are done run `nmp run build` and then visit your project on `chrome://extensions/` and click refresh `⟳`

## Contributing
Feel free to fork the project and make improvements or submit bug reports or issues.
