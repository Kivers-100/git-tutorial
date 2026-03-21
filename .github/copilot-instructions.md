# Copilot Instructions for git-tutorial

This repository is a simple JavaScript project created for learning Git version control. It contains minimal code to demonstrate basic Git operations like commits, branches, and merges.

## Architecture Overview

- **Structure**: Flat file structure with no modules or dependencies.
- **Components**: 
  - `config.js`: A basic configuration file that logs "third config8".
  - `src/main.js`: Main script logging "third8", "third file8", and 'fo'.
  - `src.text`: An ignored text file containing "Hello world".
- **Data Flow**: No data flow; purely demonstrative console outputs.
- **Design Decisions**: Kept simple to focus on Git workflows rather than code complexity.

## Developer Workflows

- **Running Code**: Execute with `node <filename>.js` (e.g., `node src/main.js`).
- **No Build System**: Direct Node.js execution without compilation or bundling.
- **No Testing**: No test files or frameworks present.
- **Git Operations**: Use standard Git commands; files are staged/committed to illustrate tutorial steps.

## Project Conventions

- **Output**: Use `console.log()` for all outputs, as seen in `config.js` and `src/main.js`.
- **File Naming**: Simple lowercase with extensions (e.g., `main.js`).
- **Ignored Files**: `src.text` is in `.gitignore`, demonstrating ignore patterns.

## Key Files and Directories

- `config.js`: Exemplifies a config file in the root.
- `src/main.js`: Primary script file in `src/` directory.
- `.gitignore`: Ignores `src.text` to show selective tracking.

## External Dependencies

None; pure Node.js without npm packages.

When adding features, maintain simplicity and focus on Git learning objectives.