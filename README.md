# Heroku Buildpack for webpack

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for web applications that use webpack.

## Usage

To use the buildpack:

1. Configure your `.buildpacks` file:

   ```
   https://github.com/heroku/heroku-buildpack-nodejs
   https://github.com/metrox/heroku-buildpack-webpack
   ```

2. Set ```WEBPACK_CONF_PATH``` variable to your webpack.config.js path for example `config/webpack/production.config.js`

3. Deploy to Heroku.
