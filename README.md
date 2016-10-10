My Markdown Resume
===================

### Download:

You can find the latest PDF version [in the releases tab](https://github.com/chancock09/resume/releases/latest).

### Build:

```
git clone https://github.com/chancock09/resume
cd resume
. /Users/chancock/context/tex/setuptex
make
```

### Requirements:

- ConTeXt
- pandoc

```
brew install pandoc

# http://wiki.contextgarden.net/Mac_Installation#Using_the_Commandline
mkdir $HOME/context
rsync -av rsync://contextgarden.net/minimals/setup/first-setup.sh .
sh ./first-setup.sh --modules=all --engine=luatex
```
