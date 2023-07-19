# Import Paper Obsidian Plugin

## What this can do
1. Input arxiv/aclanthology URL
2. Create new note for the paper

## Source
This plugin was originally created by chauff in https://github.com/chauff/paper-note-filler


## Note format

- Filename options
  - Original format
    - `{pdf identifier}`
    - `{first 3 terms of title}` 
    - `{first 3 terms of title without stopwords}`
    - `{first 5 terms of title}` 
    - `{first 5 terms of title without stopwords}`
    - `{title}`
  - Newly added format
    - `{first author last name}'{year in 2 digit} {first word of title}`
- Format:
    ````md
    # {paper title}

    {paper url}

    ```abstract
    {abstract}
    ```
    ```````

## How to import
1. Download `paper-note-filler` folder in this repository
2. Move `paper-note-filler` directry under `.obsidian/plugins`
3. Reopen obsidian vault
4. Activate `paper-note-filler` plugin from `Settings>Community Plugins`

Fore more detail, please consult the original directly ( https://github.com/chauff/paper-note-filler )