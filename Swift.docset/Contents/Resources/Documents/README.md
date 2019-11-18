# Introduction

This repo generates a docset in the [Kapeli Dash Mac App](https://kapeli.com/dash) for the Swift Programming Language.

# Getting Started

1. If you don't have brew installed first install [brew](https://brew.sh/). Enter this into your terminal:  
`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

2. Once you have you brew, you need to install [dashing](https://github.com/technosophos/dashing#readme). Enter this into you terminal:  
`brew install dashing`

3. Then you'll need to install [wget](https://pypi.org/project/wget/#description). Enter this into your terminal:  
`brew install wget`

# Downloading the Latest Version Of Swift Documentation

1. Clone the repo.

2. In the project directory run:  
`wget -k -r -p -np https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html`

3. Open a text editor (ie. VSCode), and do a search and replace for all paragraph markings (¶). Replace the (¶) with nothing.

4. Once complete run:  
`dashing build`

# Importing Into Kapeli Dash


# Integrating Dash With Alfred Workflow