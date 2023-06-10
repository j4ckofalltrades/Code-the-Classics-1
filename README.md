# Code-the-Classics
Assets from the book, Code the Classics

https://wireframe.raspberrypi.org/books/code-the-classics1

## Installing pygame on MacOS

1. Install the SDL dependencies via brew:

`brew install sdl2 sdl2_image sdl2_mixer sdl2_ttf pkg-config`

2. Install XQuartz [optional]

`brew install Caskroom/cask/xquartz`

3. Install portmidi [optional]

`brew install portmidi`

4. Install latest pygame from source

`python3 -m pip install git+https://github.com/pygame/pygame.git`

5. Verify all Pygame Tests

`python3 -m pygame.tests`

Note: Seems to work best with Python 3.10.x
