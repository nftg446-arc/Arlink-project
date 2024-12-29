# Arlink-project
Project Name: my-first-app
Branch: main
Install Command: npm ci  # or yarn install
Build Command: npm run build  # or yarn build
Output Directory: dist  # or build
pam_yubico NEWS -- History of user-visible changes.             -*- outline -*-

Clone the repo: (Which you probably already had figured out...)
(Omit the '>' below, it's the prompt.)

> git clone https://github.com/lenosisnickerboa/csgosl.git

Then build everything (see below for building for separate platforms):

> cd csgosl
> . env.sh
> make install
> make

This will download all required components, build windows and linux archives in out/windows/csgosl-windows.zip and out/linux/csgosl-linux.zip.

When the above steps have been performed you can build the different targets separately, e.g. make windows or make linux.

NOTE: You will need some basic commands like make, wget, zip, unzip, ...
