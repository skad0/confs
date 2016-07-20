# How to

## backup

`apm list --installed --bare > packages.list`

`cp ~/.atom/config.cson`

## restore

```apm install `cat packages.list` ```

`cp ./config.cson ~/.atom/`
