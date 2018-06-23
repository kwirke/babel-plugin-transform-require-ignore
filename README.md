## Fork of babel-plugin-transform-require-ignore

Fork of [babel-plugin-transform-require-ignore](https://github.com/morlay/babel-plugin-transform-require-ignore).

Original lib doesn't account for use cases where imported modules get assigned to a variable, like [file-loader](https://github.com/webpack-contrib/file-loader). This fork removes that condition.