## Simple Cv2 Wrapper

a simple wrapper for cv2 common stuff

# Installation

```pwsh
pip install simple-cv2-wrapper
```

## Usage

the most basic usage

```python
with CV2Capture(0) as video:
    for frame in video:
        video.show(frame) # video.show() also works if there is no modification on the frame
```

## Features

- access cv2.VideoCapture within context manager. which handles exits when invoking `ctrl + c` or pressing the `exit` button on the window or just pressing the letter `q` alone.
- frames can be accessed by iterating over the context manager

# Version

- _0.1.0_
  - initial release and uploaded to pypi
