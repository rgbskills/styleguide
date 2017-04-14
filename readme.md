# Setup

 * Install NodeJs with NPM [Download here](https://nodejs.org/en/)
 * Install devbridge-styleguide (globally) `npm install devbridge-styleguide -g`
 * Install Gulp (globally) `npm install gulp-cli -g`
 * cd in the directory you cloned the reposetory
 * Run `npm install` (This will install dependencies)
 * Run `gulp start-styleguide` (This will serve the API)

>If you run in to the error `Port:8889 is already in use...`, then open the project in your editor and navigate to `styleguide/config.txt` and change the port on line 13 Ex:`"serverPort": 8989,`

 * Run `python -m SimpleHTTPServer` OR custom port: `python -m SimpleHTTPServer 80` (This will we used as HTTP server)
 * navigate your browser to: `http://localhost:8000/styleguide/`