overflow-scrolling
==================

Demo of a bug in iOS Safari for -webkit-overflow-scrolling

The GitHub page demonstrates a bug where the -webkit-overflow-scrolling CSS property, when set to `touch`, doesn't add a scroll bar when switched into portrait mode on iOS Safari if the content was not scrollable in landscape.

What happens is the pre tag's text is able to fit on the screen in landscape without scroll, but when the device is switched to portrait, the scrollbar is not re-applied, so the user can't scroll to see the rest of the content.
