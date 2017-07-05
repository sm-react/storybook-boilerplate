## Storybook Boilerplate

[![Live demo](https://img.shields.io/badge/Live%20Demo-%20Storybook-brightgreen.svg)](https://sm-react.github.io/storybook-boilerplate)

[<img src="doc/logos/Storybook.png" alt="Storybook" title="Storybook" height="60">](http://storybooks.js.org)
[<img src="doc/logos/NodeJS.png" alt="NodeJS" title="NodeJS" height="60">](http://nodejs.org)
[<img src="doc/logos/webpack.png" alt="Webpack" title="Webpack" height="60">](http://webpack.js.org)
[<img src="doc/logos/react.png" alt="React" title="React" height="60">](http://facebook.github.io/react)
[<img src="doc/logos/eslint.png" alt="ESLint" title="ESLint" height="60">](http://eslint.org)
[<img src="doc/logos/Jest.png" alt="Jest" title="Snapshot Testing" height="60">](https://facebook.github.io/jest/blog/2016/07/27/jest-14.html)
[<img src="doc/logos/mocha.png" alt="Mocha" title="MochaJS" height="60">](http://mochajs.org)
[<img src="doc/logos/chai.png" alt="Chai" title="ChaiJS" height="60">](http://chaijs.com)
[<img src="doc/logos/Material-UI.png" alt="Material-UI" title="Material-UI" height="60">](http://material-ui.com)

At the heart of this project the desire to collect the best practices of application development via [React-Storybook](https://github.com/storybooks/storybook) environment. This project is transparent and friendly for developers. You do not need to eject anything. Therefore you can easily add your own configuration and extend it using any packages.

It contains the *fully-charged* setup of the Storybook with **pre-installed plugins**, configuration, quick examples, and tips. Inspired by [Create React App](https://github.com/facebookincubator/create-react-app) and [React CDK](https://github.com/kadirahq/react-cdk).

--

### Features

We mark with [<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) icon features that not implemented yet. See our further plans in the [roadmap](#roadmap) section.

- **React Storybook Addons**:

     🔋 [React Storybook Info Addon](https://github.com/storybooks/react-storybook-addon-info) - *show additional <b>information</b> for your stories*

     🔋 [Storybook Addon Notes](https://github.com/storybooks/storybook-addon-notes) - *allows you to write <b>notes</b> for your stories*

     🔋 [Storybook Addon Actions](https://github.com/storybooks/storybook-addon-actions) (included by default) - *the <b>Action Logger</b> addon can be used to display data received by event handlers*

     🔋 [Storybook Addon Knobs ](https://github.com/storybooks/storybook-addon-knobs) - *allows you to <b>edit</b> React props dynamically*

     🔋 [Storybook Addon Material-UI](https://github.com/sm-react/storybook-addon-material-ui) - *provides live <b>theme</b> creating environment to React Storybook*

- **Testing**:

     [<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) [StoryShots](https://github.com/storybooks/storyshots) - *provides [Snapshot Testing](https://facebook.github.io/jest/blog/2016/07/27/jest-14.html) for React Storybook*
 
     🔋 [Mocha](https://github.com/mochajs/mocha) and [Enzyme](https://github.com/airbnb/enzyme)

- **React ecosystem**:

     🔋 [Material-UI](http://www.material-ui.com/#/) - *via [Storybook Addon Material-UI](https://github.com/sm-react/storybook-addon-material-ui)*
 
     🔋 [React Theme Provider](https://github.com/sm-react/react-theme-provider)

- **Workflow *(via NPM scripts command)*:**

     🔋 Support for Linux, macOS, and Windows

     [<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Build your App with [Webpack](https://github.com/webpack/webpack) and [Babel](https://github.com/babel/babel)
 
     🔋 Publish transpiled code into NPM
 
     🔋 Run tests

     🔋 [ESLint](https://github.com/eslint/eslint) with the [Airbnb style guide](https://github.com/airbnb/javascript)
 
     🔋 Deploy your storybook to GitHub Pages
 
--

### Roadmap

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Add support for **Storybook 3** features

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Add [Styled Components](https://github.com/styled-components/styled-components) support

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Deploy your App to GitHub Pages

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) [storybook-addon-comments](https://github.com/storybooks/storybook-addon-comments) - *allows you to add comments for your stories*

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) [storybook-addon-options](https://github.com/storybooks/storybook-addon-options) - *set configure the Storybook UI*

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Short tutorial for using this tools

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Suggest your [feature](/../../issues) which you'd like to see here!

--

### Quick start

###### Install the project

>tip: you can skip this step if you only want to look at this project. Just open [live demo](https://sm-react.github.io/storybook-boilerplate) page and continue from [here](#you-will-see-the-demo-page-provided-by-react-storybook)

```shell
git clone https://github.com/sm-react/storybook-boilerplate.git
cd storybook-boilerplate
npm i
npm start
```

[<img src="doc/npm-start.png" align="right" class="logo" width="500" title="launching the Storybook"/>](https://raw.githubusercontent.com/sm-react/storybook-boilerplate/master/doc/npm-start.png) 

Open http://localhost:9001/ in your browser.

###### You will see the demo page provided by React Storybook.

Press `Ctrl-Shft-F` to exit from `Full screen` mode.

Two panel will appear. You will see the list of `stories` at the left panel and the bottom panel for working with themes.

Let's select another theme for this page. Do it via drop-down list at the bottom panel. Out of the box there are three themes: 'Light', 'Dark' and 'Gray'. Check out them.

[<img src="doc/left-pane.png" align="left" width="180" title="Left Storybook panel"/>](https://raw.githubusercontent.com/sm-react/storybook-boilerplate/master/doc/left-pane.png) 

Note the text field with the full theme data. You can change any property and instantly see how the result will affect the appearance of the page. But the best way to edit theme is to use `Theme Editor`. 

Click to `Show Theme Editor`. It'll open a panel with a list of all theme props at the right. Click to any colored box in this list to open the color picker tool, for example on `textColor`. Now you can move your mouse over the color swatches and see how the color of text is changing.

When you feel enough to edit your theme, you can save it for future use. Press [<img src="doc/save-btn.png" width="20"/>](#you-will-see-the-demo-page-provided-by-react-storybook) to create a JSON file with your theme. Put it to `src/themes/` folder in your project to include it to your theme list automatically. **Note**: you don't need to restart your app after adding a new theme-file to this folder, just refresh your browser. **Roadmap**: we are working to eliminate even this need to refresh the page after adding a file.

[<img src="doc/bottom-pane.png" align="right" width="500" title="Bottom theming panel"/>](https://raw.githubusercontent.com/sm-react/storybook-boilerplate/master/doc/bottom-pane.png)

Okay, now let's look at the panel on the left. In fact, our application consists of two components: `src/Header.jsx` and `src/Intro.jsx`. Selecting the appropriate items in the left-side list you switch to an isolated view of the component. It's how `React Storybook` works - allows you 'step-by-step' to create and works with React components. You can improve the quality of development by applying different addons to Storybook. Most of them is already pre-installed in this project. You will find excellent [documentation and examples](https://storybooks.js.org/) on the React Storybook website.

---

### Scripts

All scripts are avalible via `npm run <script_name>`. Mostly executable scripts are located in the '.scripts' folder of your project. In oder to keep it "transparent and friendly" we display a full CLI command which will be executed.

You can list all scripts by `npm run`

<details>
  <summary>
    <b>Linting</b> <br> `npm lint` - lints your code within `src` folder <br> `npm lintfix` - tries to fix linting errors <br>
  </summary>
  
  This project uses [ESLint](https://github.com/eslint/eslint) with the [Airbnb style guide](https://github.com/airbnb/javascript). It has some minor overrides as well. I'll [find](https://github.com/sm-react/storybook-boilerplate/blob/master/.eslintrc) all ESLint settings in `.eslintrc` file located in the root of your project. 
  
  [<img src="doc/npm-lint.png" align="right" class="logo" width="486" title="linting"/>](https://raw.githubusercontent.com/sm-react/storybook-boilerplate/master/doc/npm-lint.png)
  
  This linting scripts will check your code in `*.js` and `*.jsx` files within the `src` folder.
    
  If your IDE supports the linting settings from `.eslintrc` you'll be able to see same issues bouth from IDE and CLI.
  
  **Note**: Some [files](https://github.com/sm-react/storybook-boilerplate/blob/master/src/Intro.jsx#L1-L2) in `src` use the comments to suppress linting errors. It's up to you to continue using them or remove and change code style appropriately.

</details>

--

<details>
  <summary>
    <b>Publish to NPM</b> <br> `npm publish` - publish your code to NPM<br>
  </summary>
  
The publish script first transpille your code to ES5 and put it to `dist` folder, which is cleared before each transpillation.

[<img src="doc/npm-publish.png" align="right" class="logo" width="560" title="publish to NPM"/>](https://raw.githubusercontent.com/sm-react/storybook-boilerplate/master/doc/npm-publish.png)

This project uses [Babel](https://github.com/babel/babel) for transpilling your code with following presets:

- [es2015](http://babeljs.io/docs/plugins/preset-es2015/)

- [stage-0](http://babeljs.io/docs/plugins/preset-stage-0/)

- [react](http://babeljs.io/docs/plugins/preset-react/)

>be careful with stage-0 features because they are far from the final stage!

It's setted up to transpille all `*.js` and `*.jsx` files in your `src` folder, exept `test` and `stories` folders and `*.story.jsx` files.

You'll [find](https://github.com/sm-react/storybook-boilerplate/blob/master/.babelrc) your transpillation settings in the `.babelrc` file located in the root of your project.

In some cases you need only transpille your code, not publish. So use `npm run prepublish` and get you ES5 code in the `dist` folder.

>Transplling your code to ES5 helps to use it in any other projects without warring about babel settings of these projects.
 
**Note**: you need to set at least your own [name](https://github.com/sm-react/storybook-boilerplate/blob/master/package.json#L2) and [version](https://github.com/sm-react/storybook-boilerplate/blob/master/package.json#L3) in `package.json` before publishing. You might want to set other [fields](https://docs.npmjs.com/files/package.json) as well. 
  
  
</details>

--

<details>
  <summary>
    <b>Deploy Storybook</b> <br> `npm run deploy` - deploys your storybook to Github Pages<br>
  </summary>

Now it supports only Github Pages.

[<img src="doc/npm-deploy.png" align="right" class="logo" width="646" title="deploy to Github"/>](https://raw.githubusercontent.com/sm-react/storybook-boilerplate/master/doc/npm-deploy.png)
 
This script uses your `git` remote `origin` url to get your repo. You can check it out by `git remote get-url origin`.
 
**Note** if you get this project by `git clone` command, you need to remove current git settings and add your own repo. If you've already created your Github repo you could setup git this way:

```
rm -rf .git
git init
git remote add origin https://github.com/UserName/RepoName.git
```

You'll find your repo's adress pressing `Clone or download` button at your github repo page.

</details>

--

<details>
  <summary>
    <b>Test</b> <br> `npm run testonly` - runs mocha tests<br> `npm run test-watch` - runs tests continuously<br>
  </summary>

It will find `tests` folder within `src` and run them once.

[<img src="doc/npm-testonly.png" align="right" class="logo" width="613" title="run tests"/>](https://raw.githubusercontent.com/sm-react/storybook-boilerplate/master/doc/npm-testonly.png)
 
**Note**: we have a `svg` file imported in `<Header />` component. This script is [setted up](.scripts/run_tests/mocha_runner.js) to ignore images with such extensions.

`npm run test-watch` - starts to monitor changes in your `js`, `jsx` and `json` files

</details>

--

<details>
  <summary>
    <b>Info</b> <br> `npm run status` - displays summary information about NPM package, linting errors and mocha tests
  </summary>

#### [<img src="doc/npm-status.png" align="right" class="logo" width="764" title="run status"/>](https://raw.githubusercontent.com/sm-react/storybook-boilerplate/master/doc/npm-status.png)

</details>

---

### Contribute

We'll appreciate any help, ideas, issues and feedback!
