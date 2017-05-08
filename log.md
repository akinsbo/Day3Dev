-----------------------------eslint-plugin-react ----------------------
installed eslint in dev first
installed eslint-plugin-react
create eslint
added section:
 {
  "plugins": [
    "react"
  ]
}
{
  "settings": {
    "react": {
      "createClass": "createReactClass", // Regex for Component Factory to use, default to "createReactClass"
      "pragma": "React",  // Pragma to use, default to "React"
      "version": "15.0" // React version, default to the latest React stable release
    }
  }
}

run with: ./node_modules/.bin/eslint src/
