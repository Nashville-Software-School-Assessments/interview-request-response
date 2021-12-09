# API Request/Response Assessment

## Setting Up

1. Click the Gitpod icon above. If requested, authorize with Github.
2. After the virtual machine is set up, create a new terminal by clicking the icon at the top left of the screen and then choose `Terminal > New Terminal` 
3. One the terminal is open at the bottom, install serve with `npm i -g serve`
4. Then run the web server with `serve -l 8080`.
5. When prompted how to access your project, click "Open Browser"

## Instructions

Write code in `main.js` that requests data from the following URL (https://criminals.glassdale.us/criminals). Your task is to output the following string template for each criminal - either to the console or the DOM.

```txt
${criminal name} was convicted of ${crime} and was arrested by ${arresting officer}
```

You must be able to identify and demonstrate how to inspect the Request URL and the response data from the API.
