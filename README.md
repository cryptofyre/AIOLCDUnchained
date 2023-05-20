# Kraken Elite LCD playground

WARNING: i'm not responsible for any damege to your equipment. If anything get stuck your best option is to turn off your pc and disconnect it from power for a minute or two before restarting it.

# Installation

checkout the repository or download the latest code and install python dependencies

```
pip install --upgrade hidapi mss pillow winusbcdc>=1.5 libusb-package
```

## Usage

Ensure NZXT CAM is closed and start either the rotating demo:

```
python rotating.py
```

or the screencap demo:

```
python screencap.py
```

## License

MIT License

Copyright (c) 2023 Marco Massarotto

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
