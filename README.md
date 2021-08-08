This is a repository for Debian and Debian derivatives.

You can add to your sources like this :

curl -s --compressed "https://iontelos.github.io/repo/KEY.gpg" | sudo apt-key add -

sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://iontelos.github.io/repo/my_list_file.list"

It currently contains :

- Waffles software manager https://github.com/IonTeLOS/waffles
- Penguin's eggs remastering tool (third-party) https://penguins-eggs.sourceforge.io/

This repo is currently being tested for future use in TeLOS Linux https://teloslinux.org
