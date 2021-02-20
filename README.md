# Latex Resume
## install xelatax and fonts
[Noto fonts official website](https://www.google.com/get/noto/help/install/)
```bash
# install xeletax and fonts
sudo add-apt-repository ppa:texlive-backports/ppa
sudo apt-get install texlive-xetex texlive-math-extra fonts-font-awesome fontconfig texlive-fonts-recommended texlive-fonts-extra

# install noto fonts
mkdir ~/.fonts
cd ~/.fonts
wget https://noto-website-2.storage.googleapis.com/pkgs/Noto-hinted.zip
unzip Noto-hinted.zip
fc-cache -f -v
```

## compile tex file
```bash
xelatax cv.tex
```
