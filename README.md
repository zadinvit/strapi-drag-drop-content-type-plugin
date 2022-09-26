# Strapi plugin drag-drop-content-types
![drag-drop-preview](https://user-images.githubusercontent.com/37687705/191790500-f7bc7968-cf10-4448-a049-3350d96d2d8b.png)

## ⚠ THIS PLUGIN IS IN BETA
Be warned. Although not planned - breaking changes could happen. Unexpected things could happen. Woosh!

## ⏳ Installation

```bash
# with npm
npm i @retikolo/drag-drop-content-types
# with yarn
yarn add @retikolo/drag-drop-content-types
```

### Manually
1. Add the plugin to the `src/plugins` directory. 
2. Add this to your `config/plugins.js` file (create it, if it doesn't exist yet):
```js
module.exports = {
  // ...
  'drag-drop-content-types': {
    enabled: true,
    resolve: './src/plugins/drag-drop-content-types'
  }
}
```
3. Run `npm run build` and (re)start the app

## 🔧 Configuration
Go to `Settings` -> `Drag Drop Content Type` -> `Configuration`:
* Specify how the rank field and the corresponding title field are called in your content types. Default value are `rank` and `title`.
* Add the specified fields to your content type. With the default values this would be `title` (Text (Type: Short Text)) and `rank` (Number (Number format: integer)) 
* You will be rewared with the drag-dropable menu in the list view of all content types having the specified fields.

## 🤝 Contribute
Feel free to fork and make pull requests to this plugin. All the input is welcome!