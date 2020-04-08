
# RubberDuck It: Client Side
A front end application for the RubberDuck It Project.

## Dependencies (Set up & Installation)
* [GA React Auth Template](https://git.generalassemb.ly/ga-wdi-boston/react-auth-template) includes linters, SCSS compiler, Webpack config, NPM scripts, authentication components/routes,
* `git init`, `git add`, `git commit`
* `npm install` installs dependencies
* `npm run make-standard` reformats all your code in the JavaScript Standard Style.
* `npm run build` puts bundled styles/scripts where `index.html` can find them
* `npm run nag` code quality analysis
* `npm run start` run the development server
* `npm run deploy` on master branch w/clean directory

## Structure
* `App` renders the `Header` component & the routes, each of which render a component from `src/components`.
* `src/api/auth.js` contains all the needed `axios` calls pertaining to authentication.
* To apply component specific styles, add a file to the component's directory such as `ComponentName.scss` and then import it directly into the component with `import './ComponentName.scss'`.  This will keep your styles modularized and make it easier to make changes at the component level.
