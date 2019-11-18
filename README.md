This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn electron`

Runs the electron app in the development mode.<br />
Also view in Browser. 
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

## Build insturctions for different platforms.

You can install electron builder globally if you want.

`npm install -g electron-builder`

Build

Commands:
  electron-builder build                    Build                      [default]
  electron-builder install-app-deps         Install app deps
  electron-builder node-gyp-rebuild         Rebuild own native code
  electron-builder create-self-signed-cert  Create self-signed code signing cert
                                            for Windows apps
  electron-builder start                    Run application in a development
                                            mode using electron-webpack

Building:
  --mac, -m, -o, --macos   Build for macOS, accepts target list (see
                           https://goo.gl/5uHuzj).                       [array]
  --linux, -l              Build for Linux, accepts target list (see
                           https://goo.gl/4vwQad)                        [array]
  --win, -w, --windows     Build for Windows, accepts target list (see
                           https://goo.gl/jYsTEJ)                        [array]
  --x64                    Build for x64                               [boolean]
  --ia32                   Build for ia32                              [boolean]
  --armv7l                 Build for armv7l                            [boolean]
  --arm64                  Build for arm64                             [boolean]
  --dir                    Build unpacked dir. Useful to test.         [boolean]
  --prepackaged, --pd      The path to prepackaged app (to pack in a
                           distributable format)
  --projectDir, --project  The path to project directory. Defaults to current
                           working directory.
  --config, -c             The path to an electron-builder config. Defaults to
                           `electron-builder.yml` (or `json`, or `json5`), see
                           https://goo.gl/YFRJOM

Publishing:
  --publish, -p  Publish artifacts, see https://goo.gl/tSFycD
                [choices: "onTag", "onTagOrDraft", "always", "never", undefined]

Other:
  --help     Show help                                                 [boolean]
  --version  Show version number                                       [boolean]

Examples:
  electron-builder -mwl                     build for macOS, Windows and Linux
  electron-builder --linux deb tar.xz       build deb and tar.xz for Linux
  electron-builder --win --ia32             build for Windows ia32
  electron-builder                          set package.json property `foo` to
  -c.extraMetadata.foo=bar                  `bar`
  electron-builder                          configure unicode options for NSIS
  --config.nsis.unicode=false

See https://electron.build for more documentation.

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
