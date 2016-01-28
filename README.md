# Free Law Project Website

This is the website for Free Law Project. Like the rest of our work, it is developed in the open and can be edited by other people.

This site uses the Pelican static site generator.

## Installation

1. Make a virtualenv and activate it.

1. Install the requirements file:

        pip install -r requirements.txt

## Generating Content

Run a command like:

    /home/mlissner/.virtualenvs/free.law/bin/pelican content -s pelicanconf.py -d -r

This will use the development settings to delete the output directory before recreating it and will auto-reload whenever you change your content.

## Running a development server

Activate your virtualenv, change into the `output` directory, then run:

    python -m pelican.server

You'll find you have a server running on port 8000.

## Writing a post

Posts are easy to write, but to make it even easier, there's a template called example.md. Start there!
