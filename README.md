# xcalicon

A small date and time widget for X11 which is intended to be iconified all the
time to remain on the desktop.
Its icon and window title indicate the current day and time.

![screenshot](screenshot.png)

It was written to work with
[progman](https://github.com/jcs/progman)
but should work with any X11 window manager that handles `IconicState`
hints and shows icons in a useful manner.

## License

ISC

## Dependencies

`libX11` and `libXpm`

## Compiling

Fetch the source, `make` and then `make install`
