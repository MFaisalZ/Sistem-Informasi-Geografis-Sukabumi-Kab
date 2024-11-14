# Sistem-Informasi-Geografis-Sukabumi-Kab


Option 1: Install with NPM and a build tool


Development
Installing from the npm package registry and using a build tool is the recommended approach for most users — the more dependencies your project needs, the more likely you are to run into problems that the static hosting cannot easily resolve. With a build tool, importing local JavaScript files and npm packages should work out of the box, without import maps.

Install Node.js. We'll need it to load manage dependencies and to run our build tool.
Install three.js and a build tool, Vite, using a terminal in your project folder. Vite will be used during development, but it isn't part of the final webpage. If you prefer to use another build tool, that's fine — we support modern build tools that can import ES Modules.

# three.js
npm install --save three

# vite
npm install --save-dev vite
Installation added node_modules/ and package.json to my project. What are they?



From your terminal, run:
npx vite
What is npx?
If everything went well, you'll see a URL like http://localhost:5173 appear in your terminal, and can open that URL to see your web application.
