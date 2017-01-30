# vue-style-loader

This is a fork based on [style-loader](https://github.com/webpack/style-loader). Please refer to the original project for normal API usage.

Since this is included as a dependency and used by default in `vue-loader`, in most cases you don't even need to configure this loader yourself.

## Changes in this fork

- Fixing the issue that root-relative URLs are interpreted against chrome:// urls and make source map URLs work for injected `<style>` tags in Chrome.

- Handle Vue-specific css extraction logic during server-side rendering.

- Does not support url mode and reference counting mode.

- Removed `singleton` and `insertAt` query options. It always automatically pick the style insertion mechanism that makes most sense.

## License

MIT
