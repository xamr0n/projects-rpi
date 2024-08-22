# Raspberry Pi Projects Visualization

This project visualizes a hierarchy of Raspberry Pi projects using a radial tree layout with images and D3.js.

## Project Structure

- **HTML File**: Contains the main structure and D3.js script for rendering the radial tree.
- **JSON Data (rpi_copy.json)**: Stores hierarchical data of Raspberry Pi projects.
- **Images**: The project uses circular images to represent nodes.

## Features

- **Radial Tree Layout**: The visualization uses a radial tree structure to display the hierarchy.
- **Image Representation**: Each node in the tree is represented by an image, with a circular clip-path.
- **Dynamic Background Image**: The background circle image updates dynamically based on the hovered node.
- **Hover Effects**: Node images and text size change on hover for better interactivity.

## Installation

1. Clone the repository to your local machine.
2. Place your `rpi_copy.json` data file and any required images (e.g., `logorpi.png`, `rpilogo.png`) in the project directory.
3. Open the `index.html` file in a web browser.

## Usage

- On hovering over a node, the central image updates to reflect the hovered node’s image.
- Clicking on text nodes will open associated URLs in a new tab, if available.
  
## Dependencies

- **D3.js**: A JavaScript library for producing dynamic, interactive data visualizations in web browsers. This project uses D3.js version 6.

## Customization

- **Node Images**: Customize node images by providing URLs in the JSON data.
- **Styling**: Modify the CSS in the `<style>` section of the HTML file to change the appearance of the visualization.

## Acknowledgments

This project uses D3.js to create interactive data-driven visualizations.

## License

This project is licensed under the MIT License.
