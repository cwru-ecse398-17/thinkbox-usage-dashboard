# thinkbox-usage-dashboard

a dashboard to display power-usage data of high-power machines in Sears think[box] at CWRU.

## Setup

- clone the repo: `git clone https://github.com/cwru-ecse398-17/thinkbox-usage-dashboard.git`
- enter the repo: `cd thinkbox-usage-dashboard`
- install npm packages: `npm install` (make sure you have [nodejs](https://nodejs.org))
- install grunt: `npm install grunt-cli --save-dev`
- perform freeboard grunt setup: `node_modules/grunt-cli/bin/grunt`
- open `index.html` in a web browser
    - optionally, start a web server to serve the pages: 
        - e.g. `python -m http.server --bind localhost 8080` 
        - then go to `localhost:8080` in a web browser

## License

MIT

Primarily based on [freeboard](https://github.com/Freeboard/freeboard) (MIT license).
