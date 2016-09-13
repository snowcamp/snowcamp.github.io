# Installation

You need Ruby 2.x.y to run these pages.
You can install Ruby by using [rvm](https://rvm.io/)

On a terminal:

```
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
\curl -sSL https://get.rvm.io | bash -s stable
rvm install ruby-2.3.1
```
## Jekyll / GitHub Pages

Once Ruby installed, run in a (new) terminal:

`gem install github-pages`

(Depending on your environment, you may need root access or sudo)
## Usage

For all usage and documentation please see: <http://jekyllbootstrap.com>

You can start a Jekyll server from a terminal with the command line:

`jekyll s --watch`

Then open a browser with the url:

`http://localhost:4000/`

