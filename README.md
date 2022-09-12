# Authme Revise-Labelme

This labelme is used to label box, keypoints and multi-class label on an instance.

![Image](./doc/face-keypoints.png)

## Box with multi-class label

Labelme provide shape-based flags to label multi-class for each shape

You can load default shape-based flags with a json file (such as [file](./examples/face-flags.json))

```bash
python labelme/__main__.py ${data_folder} --labelsflags face-flags.json
```

To see [simple](./examples/) example for fast hands-on.
