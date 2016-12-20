# highlight-theme

My personal theme to highlight source code for Keynote presentations.

## Requirements

* [highlight](http://www.andre-simon.de/doku/highlight/highlight.php)

## Install

```
cp my-personal.theme /usr/local/share/highlight/themes
```

## Usage

```
highlight -O rtf {/path/to/file} --font-size 24 --style my-personal | pbcopy
```
