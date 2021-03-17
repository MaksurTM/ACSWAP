This script that cycless between audiocards on a running pulseaudio sound server.
# ACSWAP
Small shell script that serves to quickly swap between audiocards on a running pulseaudio sound server.
It uses `pactl` and switches to the next audiocard in number and then starts from the first audiocard again.
If you add any new audiocards to your system make sure to run `acswap --update`.

## Installation
1. Move to /bin/ folder.
2. Give execute perm with `chmod -x /bin/acswap`

Now you use `acswap` to switch to the next audiocard.
This script intended to be set as global keybind.
