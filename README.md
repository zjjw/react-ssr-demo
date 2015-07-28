# React Server-Side Rendering (SSR) Demo

This is a simple example of rendering React components server side, when ur primary web server is not Node.js.

## How to run

You will need node (>= 0.10), npm, python (2.7) and pip.

1. `npm install && pip install -r requirements.txt` To install the deps
2. `webpack` To build the JS
3. `npm start` Start the Node.js SSR web server
4. `python server.py` Start the Tornado web app
5. Navigate to `http://localhost:8080/hello`
