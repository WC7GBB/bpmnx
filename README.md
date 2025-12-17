# BPMN Extended (BPMNX)

A web-based BPMN 2.0 modeler that provides comprehensive editing capabilities for all standard BPMN properties.

## Overview

BPMN Extended (BPMNX) is an enhanced BPMN modeler built on top of [bpmn-js](https://bpmn.io/toolkit/bpmn-js/) that enables users to create and edit BPMN diagrams with full access to all standard BPMN 2.0 properties defined in the official specification.

## Features

- **Full BPMN 2.0 Support**: Create and edit all standard BPMN elements
- **Comprehensive Properties Panel**: Edit all standard properties for:
  - Tasks (User, Service, Script, Manual, Business Rule, Send, Receive)
  - Events (Start, End, Intermediate, Boundary)
  - Gateways (Exclusive, Inclusive, Parallel, Complex, Event-Based)
  - Processes, Sub-Processes, and Transactions
  - Data Objects and Data Stores
  - Sequence Flows, Message Flows, and Data Associations
  - Participants, Lanes, and Text Annotations
- **Data Input/Output Management**: Define and configure data inputs and outputs for tasks
- **Type System**: Built-in support for common data types (String, Int, Boolean, Decimal)
- **Import/Export**: Open and save BPMN 2.0 XML files
- **SVG Export**: Export diagrams as scalable vector graphics
- **Keyboard Shortcuts**: Efficient workflow with standard shortcuts (Ctrl+S, Ctrl+Z, etc.)
- **Drag & Drop**: Load BPMN files by dragging them into the application

## Live Demo

Try BPMNX online: **[https://wc7gbb.github.io/bpmnx/](https://wc7gbb.github.io/bpmnx/)**

## Getting Started

### Using the Online Version

Simply visit [https://wc7gbb.github.io/bpmnx/](https://wc7gbb.github.io/bpmnx/) to start modeling immediately.

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/WC7GBB/bpmnx.git
   ```

2. Open `index.html` in your web browser

No build process or dependencies required - it's a standalone HTML application!

## Usage

### Creating a New Diagram

1. Click **New** to start with a blank diagram
2. Use the palette on the left to add BPMN elements
3. Click on any element to edit its properties in the right panel

### Editing Properties

- Select any element on the canvas
- The properties panel will display all available properties
- Edit general properties like ID, Name, and Documentation
- Configure type-specific properties (e.g., Script Format for Script Tasks)
- Add and manage Data Inputs and Data Outputs for tasks

### Saving and Loading

- **Save**: Click the **Save** button or press `Ctrl+S` to download as a `.bpmn` file
- **Open**: Click the **Open** button or drag & drop a `.bpmn` file onto the canvas
- **Export SVG**: Click **Save SVG** to export the diagram as an image

## Keyboard Shortcuts

- `Ctrl+S` - Save diagram
- `Ctrl+O` - Open diagram
- `Ctrl+Z` - Undo
- `Ctrl+Y` or `Ctrl+Shift+Z` - Redo
- `+` / `-` - Zoom in/out

## Technical Details

### Built With

- [bpmn-js](https://bpmn.io/toolkit/bpmn-js/) - BPMN 2.0 rendering and editing toolkit
- Vanilla JavaScript - No framework dependencies
- HTML5 and CSS3

### BPMN 2.0 Compliance

BPMNX follows the official BPMN 2.0 specification and supports all standard elements and properties as defined in the XSD schemas.

## License

This project is open source and available for use in accordance with standard open source practices.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Support

For questions or issues, please open an issue on the [GitHub repository](https://github.com/WC7GBB/bpmnx).
