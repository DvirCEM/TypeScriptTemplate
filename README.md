# TypeScriptTemplate

A simple TypeScript project template for VS Code that compiles TypeScript on every change.

## Features

* **Automatic compilation** on file save via VS Code tasks using `tsc --watch`.
* **Modern `tsconfig.json`** with strict compiler settings for safety and consistency.
* **Basic HTML demo** updating a `<div>` with TypeScript-driven content.

## Prerequisites

* **Bun** installed (all-in-one JavaScript/TypeScript runtime and package manager) ([bun.sh](https://bun.sh/?utm_source=chatgpt.com)).
* **TypeScript** installed globally via Bun ([typescriptlang.org](https://www.typescriptlang.org/download/?utm_source=chatgpt.com), [bun.sh](https://bun.sh/docs/cli/install?utm_source=chatgpt.com)).

### Install Bun (Windows)

Use the official install script in PowerShell:

```powershell
# Run in PowerShell
iwr https://bun.sh/install | iex
```

([bun.sh](https://bun.sh/package-manager?ref=neonpie.xyz&utm_source=chatgpt.com))

Alternatively, via Scoop:

```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
iwr get.scoop.sh | iex
scoop install bun
```

### Install TypeScript Globally

```bash
bun install --global typescript
```

([bun.sh](https://bun.sh/docs/cli/install?utm_source=chatgpt.com))

## Getting Started

1. **Clone the repository**

   ```bash
   ```

git clone [https://github.com/dvircem/TypeScriptTemplate.git](https://github.com/dvircem/TypeScriptTemplate.git)
cd TypeScriptTemplate

````
2. **Open in VS Code**
3. **Run the build task**
   - Press `Ctrl+Shift+B` and select **tsc: watch – tsconfig.json** to start the compiler in watch mode.
4. **Serve `index.html`**
   - Install and use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension, or open `index.html` directly in your browser.

## Project Structure

```text
.
├── .vscode/             # VS Code settings and tasks configuration
├── index.html           # HTML entry point
├── index.ts             # TypeScript source file
├── index.js             # Generated JavaScript (gitignored)
└── tsconfig.json        # TypeScript compiler configuration
````

## Usage

* **Edit** `index.ts` to change the behavior.
* **View** `index.html` in your browser to see instant updates.

## Contributing

Contributions, issues, and suggestions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is unlicensed by default. To apply a license, add a `LICENSE` file to the repository root.")
