# RFCs

This repository houses RFCs.

## Motivation

Why have an RFC policy for your org? Read more [here](https://oxide.computer/blog/rfd-1-requests-for-discussion) and [here](https://blog.pragmaticengineer.com/scaling-engineering-teams-via-writing-things-down-rfcs/).

## Dependencies

You'll need `pandoc` for this repository.

On Mac OS X, you can install it with `brew install pandoc`.

On Windows, you can install it with `choco install pandoc`.

On Linux Distributions, check your package manager:

On Debian/Ubuntu: `apt-get install pandoc` should install pandoc.

## Scripts

To create a new RFC, run `bin/new`. This will create a new folder under `rfcs` with the left padded RFC identifier for your RFC. In there, you'll find a `README.md` file which has been filled out with some YAML frontmatter (based on your git `user.email` and `user.name`.

To create an HTML website of your current RFCs, run `bin/build`. This will build a website in the `dist` folder that houses all of your RFCs, along with a list of RFCs as the homepage.

