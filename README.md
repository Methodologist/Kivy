# KivyGUI
Requires a Python version 3.4

In order to run kivy on Windows, you will need msvcp71.dll, and msvcr71.dll in System32, and SysWOW64 for x64 OS

pip install pillow

python -m pip install --upgrade pip wheel setuptools

python -m pip install --upgrade docutils pygments pypiwin32 kivy.deps.sdl2 kivy.deps.glew kivy.deps.gstreamer --extra-index-url https://kivy.org/downloads/packages/simple/
