# linkedevents-ui-theme
Linked events UI theme support for municipality specific styling for components.

## Installation
This is a npm package which is used in https://github.com/City-of-Turku/linkedevents-ui, remove/replace city_theme in package.json with  your own package, as well as change ```"city_theme": false``` within config_dev.json with your own variable. e.g: 
```
"city_theme": "city_theme"
```

## Configuration
You can ```yarn link``` the project into your linkedevents-ui, to test styles locally. e.g:
```
//in your linkedevents-ui-theme:
yarn link

//in your linkedevents-ui:
yarn link city_theme

```
