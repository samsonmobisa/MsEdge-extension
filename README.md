# MsEdge-extension
An extension that pops up the NASA picture of the day

# Step 1: Create a manifest.json file
Every extension package must have a manifest.json file at the root. The manifest provides details of your extension, the extension package version, the extension name and description, and so on.
The following code outlines the basic information needed in your manifest.json file:

**The directories of your project should be similar to the following structure**:
└── part1
    ├── manifest.json
    ├── icons
    │   ├── nasapod16x16.png
    │   ├── nasapod32x32.png
    │   ├── nasapod48x48.png
    │   └── nasapod128x128.png
    ├── images
    │   └── stars.jpeg
    └── popup
        └── popup.html
