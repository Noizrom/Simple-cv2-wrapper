## Simple Cv2 Wrapper

a simple wrapper for cv2 common stuff

## Usage

```python
with CV2Capture(0) as video:
    for frame in video:
        frame = imutils.rotate(frame, 15)
        video.show(frame) # video.show() also works if there is no modification on the frame
```
