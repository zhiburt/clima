# clima

A viewer for Termimad.

This tiny application opens any Markdown file and displays it using **Termimad**.

Which isn't really useful as Termimad hasn't been designed to display any markdown file ([Termimad](https://github.com/Canop/Termimad) is more of an helper to let you incorporate rich text and tables in your terminal applications).

Clima is this *not a general purpose Markdown viewer* but can be used  to try out or fix some markdown you'd like to incorporate into your terminal application using Termimad and that you prefer to edit as a file.

## Installation

Download the Repository

    git clone https://github.com/Canop/clima

and build and install `clima`

    cd clima
    cargo install --path .

## Usage

To open a file in the viewer, just pass its path:

    clima README.md

If you add the `--print` option, the file is just printed to stdout, the scrollable viewer doesn't appear:

    clima -p README.md


