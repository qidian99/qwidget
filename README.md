# QWidget

## Components

### Video Player
### Charts
### Cards
### Tables
### Animation Components

## React compatibility

The widgets are fully compatibile with React. Add the following lines to `preact.config.js` will
suffice:

```js
export default config => {
  const aliases = config.resolve.alias;
  aliases.react = "preact/compat";
  aliases["react-dom"] = "preact/compat";
}
```
