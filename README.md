> Command line tool to convert images to ascii art

## Features

- Get images ascii Art
- Get GIF ascii Art

## Usage

`go run main.go --help` \
or \
`asciiArt --help`

```
Usage:
  asciiArt [flags]

Flags:
  -h, --help          help for asciiArt
  -p, --path string   path of your file for which you want to convert ASCII Art
  -w, --width int     width of final file (default 100)
```

## Command

```
asciiArt -p "path to file" // this will print with width 100

or

asciiArt -p "path to file" -w 150
```
