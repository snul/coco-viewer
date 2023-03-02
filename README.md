# COCO Viewer

Simple COCO Objects Viewer in Tkinter. Allows quick viewing on local machine.

![Example images](assets/img1.png)

## Requirements
`python3` `PIL`

## Installation

```
git clone https://github.com/trsvchn/coco-viewer.git
```

## Usage

```bash
python cocoviewer.py FOLDER 
```

The folder must have the following structure:

```
FOLDER/
- coco/
  - images/
    - image1.jpg
    - image2.jpg
    - ...
  - labels/
    - image1.txt
    - image2.txt
    - ...
  - bbox.json
```
