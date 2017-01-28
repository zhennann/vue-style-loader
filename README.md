# vue-style-loader

This is a fork based on [style-loader](https://github.com/webpack/style-loader). Please refer to the original project for normal API usage.

## Changes in this fork

- Fixing the issue that root-relative URLs are interpreted against chrome:// urls and make source map URLs work for injected `<style>` tags in Chrome.

- Handle Vue-specific css extraction logic during server-side rendering.

## License

MIT
