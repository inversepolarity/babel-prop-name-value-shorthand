# Introduction

This is a babel plugin for more convenient JSX syntax when passing props to components.

Rationale: Passing props with the same named variable is a rather common, obvious redundancy JSX could do without


Thus, Instead of:

```

 <Auth session={session} reloadSession={reloadSession} />

```

You can simply write:

```

 <Auth session reloadSession />

```

# Installation

`npm i babel-prop-name-value-shorthand --save-dev`


## NextJS/Create React App

```
//.babelrc
{
    "plugins": ["babel-prop-name-value-shorthand"]
}
```


# Known Issues

- ts(2322)