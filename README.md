# Anchor.js for Gitbook

Adds deep links to headlines using AnchorJS v4.1.0.

```js
{
  "plugins": ["anchorjs"]
}
```

The deep links to page sections are initially-hidden and pop into view on hover.
Design and behavior can adjusted in `book.json`:

```json
{
  "pluginsConfig": {
    "anchorjs": {
      "selector": "h2,h3,h4,h5",
      "icon": "#",
      "placement": "left",
      "visible": "always",
      "class": "custom-class another-one",
      "truncate": 64,
      "ariaLabel": "Anchor"
    }
  }
}
```

See [anchor.js](https://github.com/bryanbraun/anchorjs) docs for details.
