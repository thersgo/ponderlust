Ponderlust
================================================================================
A 5-button audio-only voice recorder inspired by line-based text editors.

Reason
--------------------------------------------------------------------------------
I routinely take evening walks, frequently alone, and it's basically dead silent
around me when I do so.

I have this strange condition where my mind's connected to my legs: whenever i'm
thinking or planning something, I get the urge to aimlessly walk around.
Likewise, when I walk in a quiet space, I get the urge to think about countless
different things.

I *would* like to work on my copious notes and plans in this time, but I can't
exactly walk and type in my phone (much less a computer) at the same time, both
due to having my view stuck to the screen, and both hands full (to have even a
bearable typing speed).

However, I *also* don't want to just make one long audio recording, because I
*know from experience* that I am simply far too lazy to listen through it
later, let alone try and edit or transcribe it — especially when working on my
linguistics hobby projects.

...But what if I could do edits in real-time?
...With a simple handheld device I didn't have to even look at to use?

So, picture this — a mint-tin-sized box with:
- an on/off switch,
- volume dial,
- one button per finger (thumb button on top, 4 buttons on the side),
- a microphone and speaker, and/or headphone and mic jacks.

Those 5 buttons are, in order of thumb to pinky:
- `=` shift,
- `+` add,
- `-` cut,
- `<` left,
- `>` right

So, you have a list of recordings:
- `+` starts a new recording; while recording:
  - `+` stops and inserts the recording wherever you are in the list,
  - `-` cancels the recording
- `-` deletes the recording in the current position
- `<` and `>` cycle through recordings
- `=<` and `=>` move the current recording around
- `=+` joins the current and previous (left) recording
- `=-` opens the settings
- tapping `=` plays the position (ex: "thirteen") and that recording

while playing:
	- `<` rewinds,
	- `>` fast-forwards,
	- `-` splits clip at current point,
	- `+` pauses (or continues when paused),
	- `=` stops playback

So you essentially have a (to-do) list out of small audio clips,
which you can reorder, insert into, cut up, and remove from on the fly.



### A sidenote on accessibility
As far as I'm aware, all common audio recorders are either severely reliant on
a display and complex menus for the above features, or are extremely limited
and "discreet", having a clearly... *different* intended use.

I feel like this tool could be really usable with one earbud in,
and using the buttons with one hand by your side without even looking,
while *still* being both more efficient and accessible than the current options.
