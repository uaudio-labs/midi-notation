# MIDI Notation

A LUNA Add On that shows your MIDI as standard notation, live, while you work. It comes with
**Score View**, which lays the same notation out on printable pages.

Requires LUNA 3.1.1 or later.

## Install

1. Download `midi-notation.lunaaddon` from the latest release on this repository's
   **Releases** page.
2. Double-click the file. LUNA installs it into its Add Ons folder.

To update, install the newer `.lunaaddon` the same way.

## MIDI Notation

Open it from **Add Ons > Editors > MIDI Notation** on the Timeline page. It takes the editor
panel at the bottom of the Timeline, in place of the Clip Editor; choose the menu item again
to close it.

- **Follow selection** shows the MIDI tracks selected in LUNA, stacked and lined up bar for
  bar with their names at the left. Or pick a single track from the menu.
- Shows the notes from every unmuted MIDI clip on the track's active playlist, quantized to the
  grid you choose (1/4 to 1/32). Muted notes and notes outside a clip's bounds are left out.
- Picks treble, bass or grand staff from the notes' range (split at middle C), with up to two
  voices per staff so held notes under moving parts read cleanly. Notes are tied across beats
  and bar lines.
- Follows the session's time signatures and key signatures, including changes.
- The bars run along one line that scrolls sideways. The red playhead follows the transport and
  scrolls while playing; click the score to move the playhead there.
- Updates as you edit notes in LUNA.

## Score View

Open it from **Add Ons > Windows > Score View** while a session is open.

- Letter or A4 paper, Small, Medium or Large staff size, a title (the session name unless you
  change it) and the opening tempo, with bar numbers on every system and page numbers.
- **Tracks:** all MIDI tracks (the default), the tracks selected in LUNA, or one track.
- **Print…** opens the system print dialog. Choose "Save as PDF" there to save a PDF. The
  pages fit the paper exactly, and the toolbar is hidden when printing.
- Updates as you edit notes in LUNA.

## Not supported yet

- Tuplets
- Drum notation
- More than two voices per staff (extra lines are tied through a shared voice)

## Credits

Notation is drawn with [VexFlow](https://www.vexflow.com/) (MIT License).
