
# clj-css-normalizer

### Overview

The <strong>clj-css-normalizer</strong> is a simple browser default style normalizer
CSS stylesheet for Clojure projects.

### deps.edn

```
{:deps {bithandshake/clj-css-normalizer {:git/url "https://github.com/bithandshake/clj-css-normalizer"
                                         :sha     "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"}}
```

### Current version

Check out the latest commit on the [release branch](https://github.com/bithandshake/clj-css-normalizer/tree/release).

### Changelog

You can track the changes of the <strong>clj-css-normalizer</strong> library [here](CHANGES.md).

# Usage

### Index

- [How to implement the CSS normalizer?](#how-to-implement-the-css-normalizer)

### How to implement the CSS normalizer?

Place the `normalizer.min.css` file in your HTML header, you can find it in the
`resources/public` folder of this repository:

`resources/public/normalizer.min.css`
