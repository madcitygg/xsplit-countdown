# xsplit-countdown
A tiny, self-contained countdown file to use in Xsplit for stream countdowns.

## Steps for intended usage
1. Clone the repository
2. Open `countdown.html` in any text editor
3. Change the `countdownMinutes` variable at the top to your desired number of minutes to count down to, save the file
4. Open Xsplit
5. Click 'Add' on the bottom to add a source, and click 'Media file'
6. Navigate to where `countdown.html` is on your hard drive, select it
7. Blammo, you have a super simple countdown on your stream's scene.

Personally, for broadcast times, I'd recommend copying `countdown.html` a few times, and naming them something like:
* `countdown-20min.html`
* `countdown-5min.html`

...et cetera.  Then, just change the duration in each corresponding file.  This way, you can pull up multiple countdowns easily during your broadcast if need be.

There is also a small style block near the top where you can edit any CSS properties of the text.