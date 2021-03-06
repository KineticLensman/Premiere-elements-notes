# JK's notes on Premiere Elements

Based on https://helpx.adobe.com/pdf/premiere-elements_reference.pdf

All of these notes are for the Expert view.

# Premiere elements

## Random notes

Use the template project in useful assets

Scale clips to size using FX

## Timeline

Clips in Higher tracks (e.g. Video 2) overlay clips in lower tracks

### Current time

Position the current-time indicator by
* `Drag` the current-time indicator (shift-drag snaps to markers or edge of closest clip)
* `Click` the timeline ruler
* `HOME` - move to beginning of movie
* `END`- move to end of movie
* `Left arrow` / `Right arrow` - back / forward by one frame (`SHIFT`-arrow moves by 5 frames)
* `PAGE UP` / `PAGE DOWN` - move current time indicator to previous / next clip
* Type a time value

## Clips

### Selecting a clip

* `Click` the target clip in the timeline. Automatically selects linked clips (e.g. the audio associated with a target video clip)
* `ALT-click` – only selects the target clips (i.e., linked audio/video clips are not selected)
* `SHIFT click` / `shift drag` to add more clips to a selection

### Inserting clips

`Timeline->Snap` to toggle clip snapping. Then

* `Drag` clip from Project Assets to timeline to insert it. The new clip will split an existing clip if it is dropped into the midde of it. All other clips will shift to the right
* `ALT-drag` - as above, but only linked clips will be split or moved. Other clips (e.g. soundtrack) will stay where they were. If the target was `ALT`-selected, it's linked clips will not be affected.
* `CTRL-drag` as above, but the new clip will overlay (i.e. delete and replace) the existing clip(s) 
* `Drag` clip to blank space above uppermost track in the timeline to create a track for the clip
* `Drag` clip to monitor panel – to access options such as create picture-in-picture

 

### Cutting a clip

Removing a selected clip. Lots of options. What happens depends on whether the selection includes linked clips (normally selected, i.e. video _and_ audio) or not (`ALT`-selected, i.e. just video _or_ just audio))

* `Edit->Cut` / `Ctrl-X`: Deletes selected clip. If linked clips aren't selected, the gap doesn't close (i.e. audio is left in place)
* `Edit->Delete` / `SHIFT+DELETE`: Deletes selected clip and doesn't close gap (linked or not)
* `Edit-Delete and close gap` / `BACKSPACE`: Same as Cut? If linked clips aren't selected, the gap doesn't close

### Splitting a clip

Split a clip (and linked clips, depending on what is selected):
* `Click` the Split clip button on the current time indicator
* `CTRL-k` to split the clip at the current time indicator


### Replacement

Replace clip – select in assets manager and then right click the target in the timeline


## Other useful things

`Timeline->Snap` to enable / disable snapping of clips to each other

`Clip->Reveal` in project – to show the source asset of a clip in the timeline

## Text

To edit, Select the clip and then open the Adjustments window.

The text becomes a project asset.

Can copy and paste these in the asset manager

Use the Fix button to open open an instance for editing

Rather than copying a text label in the timeline window, instead

* create the text label and set the font, colour, etc that you want
* go to the project assets window, where the new text now appears as a project asset
* right click the text label asset and select duplicate
* drag the new duplicate into the timeline and then edit its text - it doesn't affect the original!

# Useful commands

|key | Action|
|:---|:---|
|Space|start/stop replay|
|s|Toggle timeline snap|
|\\ |Fit visible|
|-|Zoom out|
|=|Zoom in|
|`CTRL-k `|Split clip|


