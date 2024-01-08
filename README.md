# Responsive Font Sizes

> Your Tailwind CSS Plugin Description

Install the plugin from npm:

```
$ npm install responsive-font-sizes
```

Then add the plugin to your `tailwind.config.js` file:

```js
// tailwind.config.js
module.exports = {
  theme: {
    // ...
    // Optional. Your plugin might not have any options at all.
    responsiveFontSizes: {
      // ...
      YOUR_PLUGIN_CUSTOM_OPTION: true,
      // ...
    },
  },
  variants: {
    // ...
    // Optional. Your plugin might not have any variants at all.
    responsiveFontSizes: ['responsive'],
    // ...
  },
  plugins: [
    // ...
    require('responsive-font-sizes'),
    // ...
  ],
};
```

This plugin will generate following CSS:

```css
/* ... */
.example-utility-class {
  display: block;
}

.custom-utility-class {
  background-color: red;
}
/* ... */
```

## License

Responsive Font Sizes is licensed under the MIT License.

## Credits

Created with [create-tailwind-plugin](https://github.com/Landish/create-tailwind-plugin).
