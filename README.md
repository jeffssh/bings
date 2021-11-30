# Better strings

usage: bings [-h] [-i] [-r] [-m MIN] file [file ...]

Better `strings`
Supports UTF-8, ASCII, UTF-16-BE, and UTF-16-LE

positional arguments: \
  file               file(s)/dir(s) to parse

optional arguments: \
  -h, --help         show this help message and exit \
  -i, --interactive  Interactively search strings (powered by fzf) \
  -r, --recursive    Recursively parse any directories \
  -m MIN, --min MIN  Minimum number of printable characters to qualify as a string
  