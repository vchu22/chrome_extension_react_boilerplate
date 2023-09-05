# Reac Chrome Extension Boilerplate
I followed the tutorial [Build a Chrome Extension With React & Webpack](https://www.youtube.com/watch?v=8OCEfOKzpAw) to build a simple Chrome extension using React.

## Run project
- Run development mode: `npm run dev`
- Run production mode: `npm run build`

When running the extension for the first time, the extension needs to be installed through the Chrome Extensions Settings page and then click on the "Load unpacked" button. Then, navigate to the project folder and select the "dist" folder generated from one of the above commands.

If extension is built through **production mode**, repeat the steps above to reinstall the extension whenever there's a change in the code. If running **development mode**, there is no need to reinstall.

To debug the popup page in Chrome Dev Tool, type in `chrome-extension://<extension_id>/popup.html` in the URL bar. `<extension_id>` can be found in Chrome Extensions Settings.