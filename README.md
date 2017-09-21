Run the following commands in project folder:
1. npm init
2. Create a .gitignore file
3. Install React
- npm install react@15.5.4 react-dom@15.5.4 --save
4. Install webpack globally
- npm install webpack@2.6.0 --save-dev
- npm install webpack@2.6.0 -g
5. Create a webpack.config.js at top level of dir
6. install babel  
- npm install babel-core@6.24.1 babel-loader@7.0.0 babel-preset-es2015@6.24.1 babel-preset-react@6.24.1 --save-dev

7. Change code to remove top script tags in index.html;  
change bottom tag to <script src="build/app.bundle.js"></script>

8. add import statements to index.jsx
import React from "react";
import ReactDOM from "react-dom";

9. Run $ webpack to compile, bundle code

10. for now, when change code, will need to rerun webpack



11. from PROPS lesson -
  npm install prop-types@15.5.10 --save



12. Webpack Development Server
$ npm install webpack-dev-server@2.5.0 -g
$ npm install webpack-dev-server@2.5.0 --save-dev

13. We can then bundle and serve our project with the following two commands:
$ webpack
$ webpack-dev-server

-- Now, projects are at http://localhost:8080

14. HHot Module Replacement - hot swapping
npm install react-hot-loader@3.0.0-beta.7 --save-dev

- Webpack Configurations to Support HMR
...
$ npm install html-webpack-plugin@2.29.0 --save-dev
