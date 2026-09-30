ANIMATION-SHRIDHAR — A.Shridhar intro animation (standalone demo)
=====================================================================
Only the STARTING experience of the old ashridhar.com:
the man-walking / lift / category video animation. No full website.

FLOW (same as original site, same video files + timings)
1. Loader -> black start screen: logo + "Click here to begin the experience"
2. Click -> title_to_lift.mp4 plays (man moving / title-to-lift animation).
   "8..0 Skip Now" countdown appears; video auto-pauses at 15 sec and
   "Pick Your Choice" fades in. Skip jumps straight to the lift video.
3. Pick one of 4 icons: Mid-segment Luxurious / Elite Residences /
   Weekend Villas & Plots / Commercial -> plays that category film
   (rCityAnimation / alora / Kalrav_new / absolute_new), pausing at each
   project name with a next-arrow to continue.
4. Film ends -> to_lift.mp4 (lift) -> back to "Pick Your Choice" (loops).
5. "View Project Details" -> end card (full site not included) + Replay.

RUN IT (pick one)
A) Double-click index.html (works, no server needed).
B) Your own terminal:
     cd "C:\Users\Administrator\Desktop\ANIMATION-SHRIDHAR"
     python -m http.server 8000
   then open http://127.0.0.1:8000/
   (NOTE: a server started by the AI tool dies immediately — start it
   yourself or use option A.)

FILES
- index.html (self-contained, vanilla JS, no internet needed)
- video/title_to_lift.mp4, to_lift.mp4, rCityAnimation.mp4,
  alora.mp4, Kalrav_new.mp4, absolute_new.mp4 (original files, ~343 MB)
- img/ (logo, 4 category icons, next_arrow, loader, favicon)
- gif/downarrow.gif

SOURCE: recovered from Wayback snapshot 20250620001514 of ashridhar.com
(see ..\NOT-NAME-YET\ashridhar_recovered + RECOVERY_HANDOFF.md).
Videos are muted (as in the original) so they autoplay after your click.
