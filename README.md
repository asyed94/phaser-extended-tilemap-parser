# phaser-extended-tilemap-parser
A library for automatically turning Tiled Map Editor objects into Phaser sprites.

This library was designed to work with a custom build of Phaser 
2.3.0 that includes Tiled image collection support, which can be found in this git repo.

From the source:

> [This library] creates sprites for any objects in the given Tiled Object Layer whose image data comes from an image collection or a tileset (has a gid). The resource used must be present in the Phaser Cache with its key the same as its filename. e.g: filename:"my-image.png", key:"my-image.png". Also, all objects must be uniquely named.