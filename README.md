# Authme Revise-Labelme

This labelme is used to label box, keypoints and multi-class label on an instance.

![Image](./doc/face-keypoints.png)

## Box with multi-class label

Labelme provides shape-based flags to label multi-class for each shape

You can load default shape-based flags with a json file (such as [file](./examples/face-flags.json))

## Example for fast hands-on

```bash
ipython --pdb -- labelme/__main__.py examples --labelflags examples/face-flags.json
```
