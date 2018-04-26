# re_academiaTimer
Recreation of the timer from the TV show "My Hero Academia."

Assets and code created from scratch. Coded in GM: Studio with Gamescript, assets created in GIMP with screencapped references from the show.

![Comparison](https://i.imgur.com/6QSZp1B.png)

![Summary of Features](https://i.imgur.com/qRNY3HX.png)

Clip from show of original (Animated): https://imgur.com/a/jStXgkG

Features:
- Functions identically to the show
- Allows for custom setting of the timer (maximum cap of 59 minutes, 59 seconds since the original did not have hours)
- HUD components are fully functional and accurate
- Play/Pause functionality, and Stop (Reset) ability

To-Do List/Known Concerns (that will probably never get done):
- Add sound effects (difficult since no clean source files)
- Interval values may spill off and be difficult to read
- Interval values are rounded
- Text listing min/sec isn't always accurate (since if the timeline is only seconds, there are no minutes to list)

Files are separated into .exe (single runtime executable for Windows), .apk (compatible with Android 7+ I believe), and the raw project files (stored in the compressed folder due to GitHub's file limitations).

Other Things:
- Raw Project Time: 3 Days
- Work Time: ~ 4 hours
- I know the numbers in the timer don't have the glow effect. I added the glow in GIMP, but any dynamically changing component (like the numbers), unless I individualized each number adding the glow effect to each, was too difficult to do.
