# Building A Custom HTML5 Video Player Using TailwindCSS and JavaScript

**HTML5 comes equipped with a native video player. It's shipped with a simple user interface, functionality, and some basic controls in the browser. And while the functionality of the default video player via the browser works perfectly, the user interface isn't so beautiful and fancy, and it's just not generally aesthetically pleasing.**

For this reason, most modern web applications and platforms like Udemy, Netflix, YouTube, and Amazon Prime don't ship the default built-in HTML5 video player to their users. Instead, they build their own customized versions with a sleek user interface to make their platforms more attractive and user-friendly.

## Project Setup

This project was setup using the Vite JavaScript template

1. Install project Dependencies:
``` shell
npm install
```

2. Start up the development server:
``` shell
npm run dev
```

## Folder & File Structure

- `public/`: This folder contains the assets for the project including favicons and also the video used for the video player.

- `index.html`: This file contains the markup for the custom HTML5 video player, including the Tailwind CSS added to the markup to style the custom HTML5 video player, including the Tailwind CSS added to the markup to style the custom HTML5 video player.

- `style.css`: This file contains the Tailwind CSS directives and the piece of code is used to customize the apperance and behavior of the default media controls provided by the WebKit browser engine (commonly used in browsers like Safari and some versions of Google Chrome) for the `video` element.

- `tailwind.config.js`: This file contains the custom configuation for Tailwind CSS

- `postcss.config.js`: This is also the configuration file for PostCSS to make Tailwind CSS work effectively.

- `main.js`: This file hourses all the JavaScript code responsible for implementing the custom features and functionality on the video player UI.
