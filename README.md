# Slides based on Beamer

## Prerequisites
You would need:
- pandoc (`sudo apt install pandoc`)
- texlive (`sudo apt-get install texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra`)

## Usage
Write your presentation using `beamer` format in markdown. See the sample markdown in this repository.

To generate `pdf` use below:

```
pandoc -t beamer demo.md -V theme:pureminimalistic  -o demo.pdf
```


## Credits
Thanks to Kai Norman Clasen for the *pureminimalist* template.

