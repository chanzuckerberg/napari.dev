# napari-dev-website

To get a local version running, [install npm](https://www.npmjs.com/get-npm), then install `http-server` with
```bash
npm install --global live-server sass
```

Finally, launch the development server with
```bash
sass --watch res/index.scss:res/index.css & live-server
```

and navigate to the specified port (by default `localhost:8080`)
