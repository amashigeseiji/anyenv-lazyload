# anyenv-lazyload

This is an [anyenv](https://github.com/riywo/anyenv) plugin that enable to load lazy instead of `anyenv init -`.

## Installation

```
mkdir -p $(anyenv root)/plugins
git clone https://github.com/amashigeseiji/anyenv-lazyload.git $(anyenv root)/plugins/anyenv-lazyload
```

## Usage

Replace `eval "$(anyenv init -)"` in your `~/.zshrc` or `~/.bashrc` to `eval "$(anyenv lazyload)"`.

## License

MIT
