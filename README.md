# paneful
Another program written to work out how to do something.  In this demo one wimp task (!animation) provides a pane for a window managed by a second wimp task (!paneful).  The pane has an adjust size icon, so it's parent window needs to be resized if the pane is resized, which is accomplished via user messaging.  If the parent window moves, it can move the pane directly, so no user messages are required for that.  The parent window also has a pause button that can be used to pause and restart the animation sown in the pane.

!animation needs to run first, then !paneful, but it shouldn't matter which exits first, it should behave fairly reasonably
