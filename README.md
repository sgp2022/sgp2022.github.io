# Hugo website for SGP 2022

> :warning: **_Do not edit `docs/` directly_**

## Example workflow

On your local machine, install hugo

    brew install hugo

Then clone this repository

    git clone https://github.com/sgp2022/sgp2022.github.io.git

Change into this directory

    cd sgp2022.github.io

Run the hugo server in the background while you're testing your edits:

    hugo server -D

Hugo is helping us have a "fancy" website, but it means things are a bit more
scattered. The goal is to push the layout/style related things into
`themes/minimalConference/*` and the content related items into
arrays/lists/maps in `config.yaml` (or `content/*.md` markdown files).

Once you're happy with your changes, then you can "deploy" your changes by
overwriting the cached version of the website in `docs/`

NOTE: We are still developing the website!!! 
!!DONT PUSH ANYTHING TO THE DOCS FOLDER YET!!

    #hugo -D -d docs

Then `git commit` your changes (including those to `docs/` and `git push`.
