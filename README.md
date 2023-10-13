# CASA-TypeScript
CASA project with TypeScript

## How to Run
Pull the repo, call `npm i` and then `npm start`. In your browser open `localhost:3000/start`.

## Steps 
In order to implement this functionality, you need to: 
- Run `npm i hmrc-frontend`
- Add styles in the `sass` gulp task (`gulpfile.js` line 34)
- Add views directory (`app.ts` line 23)
- Expose static assets (`server.ts` line 24)
- Add `@import` statement to css (`app/assets/stylesheets/application.scss` line 2)
- Add `hmrc.njk` file and `include` it in layout `head` (`main.njk` and `journey.njk` line 6)
- Call `hmrcTimeoutDialog` macro (`start.njk`)
