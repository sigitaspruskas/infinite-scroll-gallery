## Responsive web app gallery app:
*The goal of this test is to create a responsive single-page app (written in Vanilla JS and node.js) which will show a list of images retrieved from flickr API. The app should have a front-end and a back-end component,
behaving as follows:*
1. Front end, which offers two columns. Image thumbnails down the left hand side and the title of the image down the right hand side.
2. The app provides an infinite scroll experience.
3. Back-end component, written as a node module, which performs the fetching of images. Keeps my API key out of the public.
4. The app holds an open connection to the server, taking incremental updates.
5. Scroll bar on thumbnail section is hidden.
6. Enabled button that sorts images by title alphabetically (done in a simple (asc order) way).

### How to use node server and npm:
**Start a server:** 
1. Download or clone the project.
2. In terminal, type 'npm install' - installs all the node module packages that are listed package.json;
3. nodemon is installed: in terminal type 'npm run dev' -> node module runs "dev" script that launches nodemon (or type 'nodemon' if nodemon is installed globally);
4. The server is running on 5000 port, access it via http://localhost:5000;
5. **stop server : 'ctrl + C'**;

**Tips:**
1. Running server without modules: in terminal, type 'node index'. Stopping server type 'ctrl + C';
2. Starting and creating package.json file for the first time on new project: in terminal, type : 'npm init' creates package.json file.
3. Installing (as a dev dependency) nodemon package, that lets you see changes without restarting the server: in terminal, type 'npm install -D nodemon';
4. When the project is ready, you can delete node_modules folder, next time it will be installed witn 'npm install';