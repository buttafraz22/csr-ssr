# Convert Regular CSR React App to SSR React App

1. Open CSR React App.
2. Open a new VS Code Window.
3. Open Terminal and Run:

```shell
    npm init vite-plugin-ssr@latest
```
4. Copy components Folder.
5. Copy index.css and data.js to pages.index folder.
6. Copy app component to pages/index folder.
7. Edit pageshell.jsx to only render {children}.
8. Edit index.page.jsx to render <App /> Component.