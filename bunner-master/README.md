# Bunner

## Installation instructions for OS X (Catalina)

Install the dependencies as described here: https://www.pygame.org/wiki/MacCompile#Python%203%20+%20VirtualEnv%20+%20HighSierra%20+%20Pygame%201.9.x%20(Dev-Dec21)%20+%20Xcode%2010.1%20+%20Homebrew

```
brew install sdl2 sdl2_gfx sdl2_image sdl2_mixer sdl2_net sdl2_ttf
brew install Caskroom/cask/xquartz
brew install python3
```

Create a virtualenv

```
python3 -m venv .venv; source .venv/bin/activate
```

Install the latest version of pgzero requiring the latest version of pygame as a dependency

```
pip install git+https://github.com/philippkueng/pgzero.git
``` 

Start up the game and enjoy

```
python3 bunner.py
```


