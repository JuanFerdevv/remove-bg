# Remove Background with Node.js

This is a Node.js script that removes the background from an image using the `@imgly/background-removal-node` library.
## Examples

<p align="center">
  <img src="screenshots/pic1.JPG" width="400" />
  <img src="screenshots/output-image.png" width="400" /> 
</p>

## Requirements

- Node.js installed on your system.
- The `@imgly/background-removal-node` library installed.

## Installation

1. Clone this repository or copy the script to your local environment.
2. Install the required dependencies by running:
   ```sh
   npm install @imgly/background-removal-node
   ```
## Usage

1. Make sure you have an input image in the specified path (`./pic1.JPG` by default).
2. Run the script with the following command:
   ```sh
   node script.js
   ```
3. The output will be saved in the `results/` folder as `output-image.png`.


## Notes

- If the input file does not exist, the script will display an error and exit.
- Make sure you have the necessary permissions to read and write files in the specified paths.

## Contribution

If you want to improve this script, feel free to fork the project and submit a pull request. All contributions are welcome!

