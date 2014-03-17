enno-keyboard-maestro-macros
============================

Collection of useful macros for Keyboard Maestro.

Setup
-----

1. Download the macros you want. You can use the button labelled with *Download as ZIP* on the right hand side. Search via <kbd>⌘</kbd> <kbd>F</kbd> if you can't see it immediately.
2. Open the macros to import them. They can be found in a folder called *Window Manager*.

The Macros in Detail
--------------------

### Close all tabs except from active one

Does exactly what you'd think it does in Google Chrome. Shortcut is <kbd>⇧</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>W</kbd> by default. Feel free to change it to your needs.

### EnnoWindowManager

There are a lot of tools out there for managing your windows on OS X. But as a geek who likes to fiddle around I wanted to build my own thing with KM. So here's a list of shortcuts and how they resize the currently active window:

- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>←</kbd>: 50% left
- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>→</kbd>: 50% right
- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>↑</kbd>: 100% width and height
- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>↓</kbd>: 50% height, place at top
- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>-</kbd>: 50% height, place at bottom
- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>1</kbd>: 33% left
- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>2</kbd>: 33% center
- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>3</kbd>: 33% right
- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>6</kbd>+<kbd>1</kbd>: 66% left
- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>6</kbd>+<kbd>2</kbd>: 66% right
- <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd><</kbd>: switch window to other monitor

As always you can modify the shortcuts to your needs.

### iTerm Text Editing

*(works in standard Terminal.app, too)*

Gives you a little Cocoa-like text editing by mapping standard terminal shortcuts for text processing. I had a hard time remembering the standard shortcuts, so I made macros to use the ones I already know. 

- Delete whole line: <kbd>⌘</kbd> <kbd>Backspace</kbd>
- Delete word left to cursor: <kbd>⌥</kbd> <kbd>Backspace</kbd>
- Forward Delete: <kbd>Delete</kbd>
- Place cursor at line's end: <kbd>⌘</kbd> <kbd>→</kbd>
- Place cursor at line's start: <kbd>⌘</kbd> <kbd>←</kbd>
- Place cursor at word's end: <kbd>⌥</kbd> <kbd>→</kbd>
- Place cursor at word's start: <kbd>⌥</kbd> <kbd>←</kbd>

Bonus, *iTerm only* and not directly related to text editing, but handy if you're used to navigate through tabs in Chrome:

- Select Next Tab: <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>→</kbd>
- Select Previous Tab: <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>←</kbd>

### New Tweet from Notification Center

Use <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>T</kbd> in order to quickly set up a new tweet from the Notification Center. Major advantage: you get autocompletion for mentions and hashtags without using a third party client.

**Notice:** It assumes you already set up the shortcut <kbd>^</kbd> <kbd>⌥</kbd> <kbd>⌘</kbd> <kbd>N</kbd> to activate Notification Center. Look [here](http://osxdaily.com/2012/08/05/open-notification-center-with-keyboard-shortcut-os-x/ "Open Notification Center with a Keyboard Shortcut in OS X Mountain Lion") for instructions on how to do that.  
Furthermore you might need to adjust the "*Move and Click at*"-Action to your needs. Currently it assumes you only have buttons for Messages and Twitter in your Notification Center.

### Resize iPad-Images

A possibility to quickly shrink an image to 50% of its original size. Just select an image in Finder and press <kbd>^</kbd> <kbd>R</kbd>. Since it should perform pretty well you won't get a notification or something like that when it's done. Just press the shortcut and move on with your work. The macro should be fast enough to cope with it.

It also works with multiple files.

And just for clarity: the macro's name has its origin in a time when I searched for a tool to halve the image size of Retina-Display-Screenshots.

---

If you got any questions or issues let me know: enricoschlag at gmail dot com