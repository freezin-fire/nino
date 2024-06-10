# NINO - Terminal-Based Text Editor

## Overview

**NINO** (Non-Intuitive Notepad-like Operation) is a lightweight, terminal-based text editor written entirely in C. Designed for simplicity and efficiency, NINO also provides essential text editing features with advanced capabilities like syntax highlighting.
<br>
NINO being so compact and small, that by removing some of the fancy features can be used for embedded systems running linux. The output file is already only about 36KB, which can be further reduced accourding to the use case.
<br>
<br>
**Note -** Currently supporting Linux and MacOS X, support for Windows coming soon

## Features

- **Syntax Highlighting**: Supports syntax highlighting for various programming languages, enhancing readability and ease of code editing.
- **Find Function**: Easily search for text within your documents using the powerful find function.
- **Lightweight**: Minimal resource usage ensures fast performance even on older systems.
- **Keyboard Shortcuts**: Efficiently navigate and edit text using intuitive keyboard shortcuts.

## Installation

To install NINO, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/freezin-fire/nino.git
   ```

2. **Navigate to the directory**:
   ```sh
   cd nino
   ```

3. **Compile the source code**:
   ```sh
   make
   ```

4. **Run the editor**:
   ```sh
   ./nino
   ```

## Usage

### Basic Commands

- **Create a new file**:
  ```sh
  ./nino
  ```
  
- **Open a file**:
  ```sh
  ./nino filename
  ```
  
- **Save the current file**: `Ctrl-S`
- **Exit the editor**: `Ctrl-Q`

### Navigation

- **Move cursor**: `Arrow keys`
- **Jump to beginning of line**: `Home`
- **Jump to end of line**: `End`

### Editing

- **Delete character**: `Backspace`
- **Insert new line**: `Enter`

### Advanced Features

- **Syntax Highlighting**: Automatically enabled based on file extension.
- **Find Function**: 
  - Activate: `Ctrl-F`
  - Navigate through results: `Arrow Keys` to move to the next/previous occurrence, `Esc` to exit search mode.

## Contributing

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

NINO is released under the MIT License. See `LICENSE` for more details.

Feel free to modify and expand this README section according to your project's specific details and requirements.
