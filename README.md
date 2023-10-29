# Simple 3D Renderer in Java Swing

## Description

This project is a basic 3D renderer built using Java and Swing. It utilizes the Painter's algorithm and z-buffering to handle the depth of objects. The renderer currently supports basic rotations in both the horizontal and vertical directions.

## Features

- 3D Object Rendering
- Rotation Control via Sliders
- Depth Handling using Z-buffer

## How to Run

1. Compile all the Java files: `javac *.java`
2. Run the `DemoViewer` class: `java DemoViewer`

## Classes

### `DemoViewer`

The main class setting up the UI and connecting all parts.

- **Methods**:
  - `main`: Sets up the UI and initializes other classes.

### `Vertex`

A simple class to represent 3D points with x, y, z coordinates.

### `Triangle`

Represents a 3D triangle with vertices and a color.

### `Matrix3`

A 3x3 matrix utility class for transformations.

- **Methods**:
  - `multiply`: Multiplies two 3x3 matrices.
  - `transform`: Transforms a vertex.

## Controls

- **Horizontal Rotation**: Use the bottom slider to rotate the object horizontally.
- **Vertical Rotation**: Use the right-hand side slider to rotate the object vertically.

## Helper Methods

- `getShade`: Calculates the shaded color based on an angle.
- `inflate`: Subdivides the triangles for better rendering.

## Limitations

- Currently, only wireframe rendering is supported.
- No support for user-uploaded objects; object shape is hardcoded.

## Future Enhancements

- Support for texture mapping
- More interactive UI to upload 3D objects
- Additional rotation and zoom features

## Author

Dany Marcha

