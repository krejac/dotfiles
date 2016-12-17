# Dotfiles for macOS

:rotating_light: **WARNING**: Running this *will* change the behaviour of macOS quite drastically. :rotating_light:

![screen shot](https://github.com/krestenjacobsen/dotfiles/blob/master/screenshot.png)

## Usage

Clone this repository.

```bash
git clone git@github.com:krestenjacobsen/dotfiles.git
```

Run setup.

```bash
source ./setup
```

Wait as setup runs - can take a few hours depending on your internet connection and Mac.

## FAQ

### What's installed?

Well I'm probably not going to update this readme very often, so you'd better check out  [`setup`](https://github.com/krestenjacobsen/dotfiles/blob/master/setup) for the nitty gritty details. But I always install **Xcode cli-tools**, **Brew**, **Caskroom** and **Python**.


### What settings are changed?

See [`.osx`](https://github.com/krestenjacobsen/dotfiles/blob/master/.osx).

### What do all those .bash-files do?

Nothing ireversible - if you backup your home catalog before running `setup` (they only change the Terminals behaviour). See  [The Lumber Room](https://shreevatsa.wordpress.com/2008/03/30/zshbash-startup-files-loading-order-bashrc-zshrc-etc/) for a thorugh walkthrough.

### That about that Terminal theme though?

That's stolen from [Nathan Buchar's repo](https://github.com/nathanbuchar/atom-one-dark-terminal). (Hope he forgives me.)

### Why are you doing this?

Because I like it.
