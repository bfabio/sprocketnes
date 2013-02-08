`sprocketnes` is an as-yet-incomplete emulator for the Nintendo Entertainment
System written in the Rust programming language.

Its purpose is to serve as a *technology demonstration* to show off how the
Rust programming language is suitable for systems software such as emulators.
It's also designed to be a relatively clean example codebase, showing off
various Rust idioms. The Rust garbage collector is not used in this project,
and unsafe code is kept to a minimum.

The NES was chosen for this project because:

* It's familiar to most hackers.

* It's a reasonably simple system to emulate.

* Because of its popularity, its workings are relatively well-documented.

* It requires decent processing power to emulate accurately with proper
  graphics and sound, so it's a good demonstration of the performance of Rust
  code.

There are numerous demos and games available for free for use with this
emulator at http://nesdev.com/.

Enjoy!
