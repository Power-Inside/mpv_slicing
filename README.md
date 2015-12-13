(Forked) Lua script for mpv to cut fragments of the video with the same codec and container of the original file.

#### Usage

Make sure you have FFmpeg installed. Put `slicing.lua` to `~/.config/mpv/scripts/` or `~/.mpv/scripts/` directory to autoload the script or load it manually with `--script=<path>`.

Press `c` first time to mark the start of the fragment. Press it again to mark the end of the fragment and write it to the disk. Press `a` to toggle uncompressed audio capturing (default on). By default output videos will be placed in the current directory (where the mpv is invoked).

You could change key bindings and all parameters of the output video by editing your `input.conf` and `lua-settings/slicing.conf`.

#### License

mpv_slicing - Cut video fragments with mpv

Originally written in 2015 by Kagami Hiiragi <kagami@genshiken.org>.

To the extent possible under law, the author(s) have dedicated all copyright and related and neighboring rights to this software to the public domain worldwide. This software is distributed without any warranty.

You should have received a copy of the CC0 Public Domain Dedication along with this software. If not, see <http://creativecommons.org/publicdomain/zero/1.0/>.
