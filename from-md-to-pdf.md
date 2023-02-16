# Using Pandoc for converting MD file to PDF
## About
I wanted to quickly convert my README.md into a PDF easy to share.

So I did quick research online and I found [Pandoc](https://pandoc.org/) for Linux.

It's quite easy to use.

## Installation
```shell
sudo apt-get install pandoc texlive-latex-base texlive-fonts-recommended texlive-extra-utils texlive-latex-extra
```

## Usage
```shell
pandoc README.md -o pdf/marco-rapaccini-cv.pdf -V colorlinks=true
```

## Additional info
* [Useful Blog article](https://blog.podkalicki.com/markdown-to-pdf-quick-howto-for-linux-ubuntu/)
* [Official Docs Installation](https://pandoc.org/installing.html)
