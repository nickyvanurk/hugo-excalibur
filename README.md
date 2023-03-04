# Excalibur

A responsive, clean and simple [Hugo](http://gohugo.io) theme for a personal website.

:dagger: [Demo](https://nickyvanurk.github.io/hugo-excalibur/)

## Getting Started

### Installation
1. Create a new Hugo site:
```sh
hugo new site excalibur
```

2. Clone this repository into the `themes` directory, adding it as a [Git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules):
```sh
cd excalibur
git init
git submodule add https://github.com/nickyvanurk/hugo-excalibur.git themes/excalibur
```

3. Add this line in the `config.toml` file:
```toml
theme = 'excalibur'
```

4. Start Hugo's development server:
```sh
hugo server
```
