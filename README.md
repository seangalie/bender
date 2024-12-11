# Bender
*Bender* is a simple helper script to configure a basic Debian 12 installation post-install.

## About the Script
A while ago, I wrote a script to configure *Fedora* called [Bespoke](https://github.com/seangalie/bespoke) when I needed it and it was below the horizon of larger automation tools.  Recently, I have been working with Debian more often, which meant it was time for a helper that knew `apt` (or `nala`) as well as *Bespoke* knew `dnf` (or `rpm-ostree`).  The name is inspired by the classic [Don't Break Debian](https://wiki.debian.org/DontBreakDebian) page that is inevitably the answer on too many forum posts about customizing the distribution - since we're only bending the rules a little bit with this tool (and using `backports` wherever appropriate).

## Why not ... (insert other option here)?
 - Short answer - because it works and it largely keeps within the Debian ecosystem.
 - Long answer - because I don't want to get into making larger automation configurations for simple setups, especially when I'm just playing with a hardware repair or refurbishing an old PC.

## How to use this script
 - Clone the repository using the command `git clone https://github.com/seangalie/bender.git`
 - Switch into the cloned directory using `cd ./bender/`
 - Remember to make the script executable with `chmod +x bender.sh`

## Using Fedora?
This script has a Fedora-oriented version called [Bespoke](https://github.com/seangalie/bespoke) for Fedora 40 and 41 installations.

## License
*Bender* is released under the [MIT License](https://opensource.org/licenses/MIT).
