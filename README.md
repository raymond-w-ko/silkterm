# silkterm
A terminal emulator for Linux that is smooth as silk.

The goal is to build a terminal emulator that:
* Has a separate decode and render thread.
* Has no flicker, especially in `tmux` when a split window has something with a lot of activity going on (like compiling).
* Uses OpenGL to achieve VSync independent of any backend.
* Is minimal and programmer/hacker oriented, like `st`.
