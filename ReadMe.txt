 
### mpd Mod for Minetest
(c) 2017 orwell96
This mod is licensed under the LGPL 2.1 license.

Adds an easy but powerful background music backend.

## Usage:

For all players:
/mvolume <volume>
Set your individual music volume or disable background music (/mvolume 0). Saved across server restarts.
/mpd_list: list available music

With mpd privilege:
/mpd_play <id>: play a song
/mpd_stop: stop the current song. Unless /mpd_play or /mpd_next are invoked, no more music is played
/mpd_next [time]: Play the next song after [time] seconds, immediately if omitted.

## Votes:
This mod integrates with the [vote] mod by rubenwardy (https://github.com/minetest-mods/vote)
/vote_mpd_next - vote to start next song
/vote_mpd_play <id> - Vote to play certain sing



================================================================================
