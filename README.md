# visx-d3-react-crypto-tracker

# 🚀 Javascript full-stack 🚀

## MERN Stack

### React / Express / MongoDB / TypeScript / Material UI / Coingecko API

https://github.com/coding-to-music/visx-d3-react-crypto-tracker

https://visx-d3-react-crypto-tracker.herokuapp.com

https://visx-d3-react-crypto-tracker.onrender.com

by Arif Rahman https://github.com/ayepRahman

https://github.com/ayepRahman/react-crypto-tracker

https://cryptotracker.ayeprahman.com

https://dev.to/ayeprahman/how-i-build-crypto-tracker-chart-with-react-4k9h

```java
const secret = process.env.JWT_SECRET;
mongoose_1.default.connect(`${process.env.MONGODB_URI
```

## Deploying to Render

This plugin will extract info from Heroku and put it into a Docker file.

```java
heroku plugins:install @renderinc/heroku-import
```

Output:

```java
warning ../../../package.json: No license field
warning ../../../../../../package.json: No license field
warning "eslint-config-oclif > eslint-config-xo-space@0.27.0" has incorrect peer dependency "eslint@>=7.20.0".
warning "eslint-config-oclif > eslint-plugin-mocha@9.0.0" has incorrect peer dependency "eslint@>=7.0.0".
warning "eslint-config-oclif > eslint-plugin-unicorn@36.0.0" has incorrect peer dependency "eslint@>=7.32.0".
warning "eslint-config-oclif > eslint-config-xo-space > eslint-config-xo@0.35.0" has incorrect peer dependency "eslint@>=7.20.0".
warning "eslint-config-oclif > eslint-plugin-unicorn > eslint-template-visitor@2.3.2" has incorrect peer dependency "eslint@>=7.0.0".
warning "eslint-config-oclif > eslint-plugin-unicorn > eslint-template-visitor > @babel/eslint-parser@7.16.3" has incorrect peer dependency "eslint@^7.5.0 || ^8.0.0".
Installing plugin @renderinc/heroku-import... installed v1.1.0
```

```java
heroku render:import --app visx-d3-react-crypto-tracker
```

Output:

```java

=== Gathering information about Heroku app
Verifying Heroku app exists and CLI is logged in... ✔️
Verifying app is using a single, official Heroku buildpack... ✔️
Getting stack image... heroku-20
Getting and translating plan... Heroku Free $0/mo --> Render Free $0/mo
Getting instance count... 1
Getting custom domains... 0 custom domain(s)
Getting environment variables... 2 environment variable(s)
Getting add-ons... 0 add-on(s)

? Select addons to import.

Create render.yaml file and Dockerfile.render? This will overwrite any existing files with the same name. (y/n): y
Generating render.yaml file... done
Generating Dockerfile.render... done

=== Environment variables excluded from render.yaml
The following environment variables were not included in the generated
  render.yaml file because they potentially contain secrets. You may need to
  manually add them to your service in the Render Dashboard.

- JWT_SECRET:

=== Follow these steps to complete import of service(s) and database(s) to Render
1. Add, commit, and push the generated render.yaml and Dockerfile.render to GitHub or GitLab.
2. Go to https://dashboard.render.com/select-repo?type=iac
3. Search for and select this repository.
4. Verify the plan showing the resources that Render will create, and
   then click 'Create New Resources'.
5. After the resources are deployed, you may need to manually add
   the above environment variables to your Web Service in the Render Dashboard.
   They were not included in the generated render.yaml because they potentially
   contain secrets.
```

![Alt Text](./src/assets/dc.gif)

Recently, I visit a crypto tracker [site](https://coinmarketcap.com/currencies/bitcoin/) to check DogeCoin prices to see whether it going to the moon 🚀

![Alt Text](https://media.giphy.com/media/Ogak8XuKHLs6PYcqlp/giphy.gif)

I was curious about how to build a simplified version on that site using React, other libraries, and tools out there.

So I did research to find which API to use and came across a free, reliable, and comprehensive API from the team 🦎[CoinGecko](https://www.coingecko.com/en/api).

At the same time, my goal also was to focus to find a low-level visualization tool that comprises the power of using D3 with React, flexibility, optimized speed, and bundle sizes. And I came across [Visx](https://airbnb.io/visx/) from Airbnb.

Some of the features that I had in mind are,

- Listing all supported coins price, market cap, and volume and market-related data.
- Display coin prices in a chart with a time filter and brushing capability to select a time range.

For this project, I will be using,

- reactjs with typescript
- visx for visualization
- styled-component for styling
- coingecko api
- material-ui for ui components.
- and other libraries.

Check out my blog on how i build this project https://dev.to/ayeprahman/how-i-build-crypto-tracker-chart-with-react-4k9h

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

# react-crypto-tracker

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/visx-d3-react-crypto-tracker.git
git push -u origin main
```

## Heroku

```java
heroku create visx-d3-react-crypto-tracker
```

## Heroku MongoDB Environment Variables

```java
heroku config:set


heroku config:set JWT_SECRET="secret"

heroku config:set PUBLIC_URL="https://visx-d3-react-crypto-tracker.herokuapp.com"
```

## Push to Heroku

```java
git push heroku

# or

npm run deploy
```
