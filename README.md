# mdpress

This is a tool that converts markdown files to presentations using [impress.js](https://github.com/bartaz/impress.js/).

# Example

[This presentation](http://static.adit.io/mdpress/default) was created from [this markdown file](https://raw.github.com/egonSchiele/mdpress/master/examples/demo.md).

[This presentation](http://static.adit.io/mdpress/obtvse) was created from the same markdown file and a different stylesheet using `mdpress -s [stylesheet name]`.


## Advantages

- dead simple, works with any markdown file
- comes with a beautiful default stylesheet + more styles (more styles TBD) ... no need to write your own
- ...but you can write your own easily if you want!
- comes with [prettify](http://code.google.com/p/google-code-prettify/) integrated, does code highlighting out of the box
- has an auto-update mode; update your markdown file and mdpress will update your presentation automatically
- quick install as a ruby gem
- presentations are tiny and easy to distribute
- presentations are easy to read as a plain text file

## Install

	gem install mdpress

## Usage

	  mdpress [url or filename.md]

This creates a directory named `filename`. Start the presentation by opening up `index.html`.

[See full usage](http://egonschiele.github.io/mdpress/) (it's easy!).

## Mdpress in the wild

- There's a [debian package](http://ftp-master.debian.org/new/mdpress_0.0.14+debian-1.html) in progress.
- Here's a [Yeoman generator](https://github.com/btholt/generator-mdpress) for mdpress.

## Contributing

To contribute a new stylesheet, follow these steps:

1. Fork this repo.
2. Place your new stylesheet in `lib/impress_css/[your stylesheet name].css`
3. Send me a pull request!

## Contributors

- [Mte90](https://github.com/Mte90)
- [linopolus](https://github.com/linopolus)
- [kmlawson](https://github.com/kmlawson)
- [guidokessels](https://github.com/guidokessels)

Copyright (C) 2013 by Aditya Bhargava (MIT license)
