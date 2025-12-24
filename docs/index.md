# Welcome to Docs

Lets build something amazing but this time with documentation.

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    config.py    # This is a config file.
    memory/
        shortterm.py  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


## Code 

``` py title="bubble_sort.py" linenums="1" hl_lines="2-3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```