> Command line tool to convert images to ascii art

## Features

- Get images ascii Art
- Get GIF ascii Art

## Usage

`go run main.go --help` \
`go run main.go -p pikachu.png` \
`go run main.go -p pikachu.png -w 50`

`asciiArt --help` \
`asciiArt -p pikachu.png` \
`asciiArt -p pikachu.png -w 50`

```
Usage:
  asciiArt [flags]

Flags:
  -h, --help          help for asciiArt
  -p, --path string   path of your file for which you want to convert ASCII Art
  -w, --width int     width of final file (default 100)
```
