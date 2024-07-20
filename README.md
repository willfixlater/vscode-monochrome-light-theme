# my-monochrome-light README

## Requirements
- Node 20.9.0+ (LTS)

## Getting  Started

### Install local deps with
```bash
npm i
```

### Package the extension to prepare it for local installation
```bash
npx vsce package
```

That should create a file in the project directory with a name like:
`my-monochrome-light-<version>.vsix`

### Install a local extension
From inside VS Code, hit ctrl+shift+p to launch the command palette and search
for the command: `Extensions: Install from VSIX...`. Then from the Explorer
window it launches, navigate to the `.vsix` file created in the previous
section and select it.