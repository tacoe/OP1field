# Better OP-1 Field Support for Ableton Live
OP-1 Field works with Ableton Live out of the box, but only for basic not playing, not much else.  
Install this script to enrich the functionality of your OP-1 Field as a controller so you don't have to reach for mouse or keyboard as much while you're building your songs. It adds:
* Transport controls (play, stop, record)
* Track toggles
* Navigation in session view
* Playhead control in arrange view

This script works with Ableton Live 12 and was last tested against Ableton Live Suite 12.2.1. It was tested on MacOS 15.5, but should work on Windows as well.

## Installation
1. Download and unzip 'OP1field.zip' from https://github.com/tacoe/OP1field/releases
2. Open Live and find "Places" in the left-hand browser, under that, select "User Library"
3. In the list next to it (which has 'Clips', etc), right-click select 'New Folder' and name it "Remote Scripts". Skip this step if the folder already exists.
4. Richt-click the folder and select 'Show in Finder', locate the unzipped 'OP1Field' folder and drag it into the "Remote Scripts" folder in Ableton Live.
5. Close then re-open Live.

## Setup and operation
* In Live's Settings Dialog, go to 'Link, Tempo & MIDI', then select the Control Surface dropdown and select 'OP1Field', then in the 'Input' dropdown select 'OP-1'. Tap the PLAY button on your OP-1 Field to verify functionality: the song should start playing.
* On your OP-1 Field, press SHIFT-COM, then 2 to go into CTRL mode. Hit SHIFT, turn the BLUE button until it says `01`, the OCHRE button until it says `REL`, and the gray button until it says `ON`.

## Usage
* `REC`: Session record
* `PLAY`: Global play
* `STOP`: Global stop

* `LIFT`: Undo
* `DROP`: Redo
* `SCISSORS`: Delete clip

* `3/LOOP`: Toggle loop
* `METRONOME`: Toggle metronome
* `BUBBLE`: Toggle arranger/session view

* `MIC`: Toggle arm on current track. This disarms all other tracks.
* `COM`: Toggle mute on current track. 
* `ARP`: Toggle solo on current track. This unsolos all other tracks.

Encoders:
* `BLUE`: -
* `OCHRE`: -
* `GRAY`: 
  * when in session: `TURN` to change selected scene, `PUSH` to play selected scene 
  * when in arrange: `TURN` to move the playhead
* `ORANGE`: `TURN` to change selected track, `PUSH+TURN` to change selected track volume
