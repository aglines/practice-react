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
