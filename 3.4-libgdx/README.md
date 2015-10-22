# libGDX

![screenshot](screenshot.jpg)

## Description

Fork the [Minicraft](https://github.com/TIY-Charleston-Back-End-Oct2015/Minicraft) project. Write the necessary code to make the player walk around and stuff.

## Requirements

* Tell the project where to find the `assets` folder.
  * Go to Run -> Edit Configurations...
  * Change the "Working directory" to point to the `core/assets` subfolder
* Copy in the `move` method from `HelloGame` and define whatever variables it needs.
* Make the game draw the correct sprite (down, up, left, right) based on which direction you are going.
* Use a `FitViewport` to make the game scale as the window is resized.
* Prevent the player from walking outside of the screen.
* Optional
  * Create an `OrthogonalTiledMapRenderer` in the `create` method that loads the "level1.tmx" file.
  * Call the `render` method in the `OrthogonalTiledMapRenderer` right before `batch.begin()`.
  * Draw another character (using the exact same images) that just moves in one direction.
