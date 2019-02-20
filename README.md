# igemnace's scripts

These are my personal everyday-use scripts.

By personal, I mean *really* personal. When I publish scripts on other projects,
I take care to be as portable as is required by my projects' audience.

Not this time.

These scripts are as portable as I demand them to be, and for personal use I
tend to demand more functionality than portability. None of this is general
either; they cater to my exact use case, so expect to modify if your use case
differs (which it more than likely will), even by a tiny bit.

I leave it to the user's good judgment. **Caveat emptor**.

## Pre-installation

All scripts are written in bash.

Most of my convenience scripts rely on one or more tools to do stuff with UI.
Here's a non-exhaustive list:

- GNU coreutils
- xsel
- xdotool
- fzf
- rofi
- zenity

As long as you don't do something dumb (like run `rofi-nmcli` without neither
`rofi` or `nmcli`), you should be just fine.

## Installation

If you're me, great. Just `binify` all of these.

If you're not me, grab a script you like, modify to your needs, then place
somewhere in your `$PATH`.

## Licensing

If anyone else sees this and wants to use it, go ahead.

This project is licensed under the Unlicense and is entirely under public
domain.
