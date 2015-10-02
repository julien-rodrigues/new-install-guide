New Mac install guide
=====================

Making a new and fresh install of MacOS can be quite boring when you need to search and try to remember what you will need on this clean environment. That's why I made this little guide. This guide is made for my needs but if it can work for someone else, why not push it to Github.

# Prerequisites
** BACK-UP YOUR DATA ** : No matter what is the post installation plan, you'll need your data back on your system. Push all your code, sync your Dropbox, save all the files you want to an external Drive, ... And don't forget about your softwares preferences!! If you can export them, do it. Having to configure every single piece of software again and again is a pain in the ass. Really.

# Softwares
## Development
- Atom (use config configs/atom.md), Webstorm (use export in files/)
- iTerm2 (use export in files/)
- Chrome, Firefox, IE (<-- KIDDING! DON'T DO THAT)
- XCode
- Filezilla or Transmit

## Design
- Affinity or Sketch 3

## Music
- Ableton 9, Logic Pro X
- Soundflower
- All the plugins for the hardware (Maschine, Keyboards, ...)

## Other
- Android File Transfer
- Dropbox
- Evernote
- Goofy, Skype, Slack
- Pages
- KeePassX
- Spectacle
- Spotify, VLC

# Development environment
I mainly (not to say only) work with JavaScript. So my dev environment reflects that.

## Node
Install Node and once it's done make the ugly no sudo trick.
```
# http://stackoverflow.com/a/21712034
npm config set prefix ~/npm

```
I know it's not ideal and not a good thing, but that does it for me. Of course install everything needed for development (Gulp, etc) and complete the config using the config (configs/node.md)

## Homebrew
This is life.

## ZSH
Use ZSH because... because yolo.
Don't forget to install oh-my-zsh using the config file in the files folder.

## SH Tools
- htop (via Homebrew)

## GIT
See configs/git.md
