enno-keyboard-maestro-macros
============================

Collection of useful macros for Keyboard Maestro.

Setup
-----

1. Download the macros you want. You could use the button labelled with *ZIP* at the top next to the clone address. Search via ⌘F if you can't see it immediately.
2. Open the macros to import them.

The Macros in Detail
--------------------

### EnnoWindowManager

There are a lot of tools out there for managing your windows on OS X. But as a geek who likes to fiddle around I wanted to build my own thing with KM. So here's a list of shortcuts and how they resize the currently active window:

- **^⌥⌘←**: 50% left
- **^⌥⌘→**: 50% right
- **^⌥⌘↑**: 100% width and height
- **^⌥⌘↓**: 50% height
- **^⌥⌘1**: 33% left
- **^⌥⌘2**: 33% center
- **^⌥⌘3**: 33% right
- **^⌥⌘6**+**1**: 66% left
- **^⌥⌘6**+**2**: 66% right

Of course you can as always modify the keys to your needs.

### New Tweet from Notification Center

Use **^⌥T** in order to quickly set up a new tweet from the Notification Center. Major advantage: you get autocompletion for mentions and hashtags without using a third party client.

**Notice:** It assumes you already set up the shortcut **^⌥⌘N** to activate Notification Center. Look [here](http://osxdaily.com/2012/08/05/open-notification-center-with-keyboard-shortcut-os-x/ "Open Notification Center with a Keyboard Shortcut in OS X Mountain Lion") for instructions on how to do that.  
Furthermore you might need to adjust the "*Move and Click at*"-Action to your needs. Currently it assumes you only have buttons for Messages and Twitter in your Notification Center.

### Resize iPad-Images

A possibility to quickly shrink an image to 50% of its original size. Just select an image in Finder and press **^R**. Since it should perform pretty well you won't get a notification or something like that when it's done. Just press the shortcut and move on with your work. The macro should be fast enough to cope with it.

It also works with multiple files.

And just for clarity: the macro's name has its origin in a time when I searched for a tool to halve the image size of Retina-Display-Screenshots.

---

If you got any questions or issues let me know: enricoschlag at gmail dot com