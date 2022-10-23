# Introduction

Passing props with the same named variable is a rather common, obvious redundancy JSX could do without

Thus, Instead of:

```

 <Auth session={session} reloadSession={reloadSession} />

```

You can simply write:

```

 <Auth session reloadSession />

```

# Usage

### Installation

`npm i babel-prop-name-value-shorthand --save-dev`

### .babelrc

```
{
    "plugins": ["module:babel-prop-name-value-shorthand"]
}
```

### Example

-   [Codesandbox](https://codesandbox.io/s/babel-prop-name-value-shorthand-6z0g6z?file=/pages/index.js)


## Known Issues

-   ts(2322)
