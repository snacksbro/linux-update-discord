# Linux Discord Updater
Are you criminally lazy like me? Do you want the upgrade of Discord to be automated instead of having to open software center twice a week as it updates? Do you wish somebody else would just get around to it already? If your answer is yes to all of those questions, this bash script is for you!

## What It Does
1. Downloads the latest Discord
2. Installs it
3. Gets rid of the update file automagically

## What It Needs
* wget, should come automatically installed, but if not `sudo apt install wget`
### Can't you just use cur-
We already established that I'm criminally lazy.

## Wat Do?
Drop the `update-discord` file into `/bin`. That's literally it, then you'll be able to just type in `update-discord` anywhere in your system and it'll do the work for you. It will request sudo privileges during the install so dpkg can do it's work.

## I Don't Like The Name The Name Sucks
`mv update-discord whatever-nerd` and drop it in `/bin`.

## I Can't Put Stuff In /bin :(
Skill issue. Also you could just make a [bash alias](https://linuxize.com/post/how-to-create-bash-aliases/) or even just run the file manually: `./update-discord`.

