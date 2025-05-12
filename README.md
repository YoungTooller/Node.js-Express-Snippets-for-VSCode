# Node.js Express Snippets for VSCode

A collection of handy VSCode snippets for rapid development with Node.js, Express, and Mongoose. This repository includes two versions: one for JavaScript (ESM) and one for TypeScript.

---

## 📂 Contents

- [Description](#description)
- [Installation](#installation)
- [Available Snippets](#available-snippets)
  - [JavaScript (ESM)](#javascript-esm)
  - [TypeScript](#typescript)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## 📝 Description

This repository provides two sets of VSCode snippets designed to speed up backend development using Node.js with Express and Mongoose:

- **JavaScript version** - for projects using modern ES modules without types.
- **TypeScript version** - fully typed and adapted for TypeScript projects.

Snippets cover:

- Express server setup with `helmet`, `morgan`, and router mounting
- Route creation with proper async error handling (`try/catch`)
- MongoDB connection via Mongoose
- Basic Mongoose schemas with methods, virtuals, hooks, and indexes
- Common HTTP responses with appropriate status codes
- And much more!

---

## ⚙️ Installation

1. Clone this repository or download the snippet files:

- `git clone https://github.com/YoungTooller/Node.js-Express-Snippets-for-VSCode.git`

2. Copy the snippet files to your VSCode user snippets directory:

- Windows: `%APPDATA%\Code\User\snippets\`
- macOS: `~/Library/Application Support/Code/User/snippets/`
- Linux: `~/.config/Code/User/snippets/`

3. Place:

- [js_express.code-snippets](/snippets/js_express.code-snippets) - for JavaScript
- [ts_express.code-snippets](/snippets/ts_express.code-snippets) - for TypeScript

4. Restart VSCode (recommended).

---

## 🚀 Available Snippets

### JavaScript (ESM) // TypeScript

| Prefix          | Description                                           |
|-----------------|-------------------------------------------------------|
| `exindex`       | Basic Express server with try/catch in `app.listen`   |
| `exindexfull`   | Full server setup with `helmet`, `morgan`, and router |
| `exerror`       | Centralized Express error handling middleware          |
| `muser`         | Basic Mongoose user schema                              |
| `exroute`       | Express route declaration with method and handler      |
| `exfunc`        | Exported async function handler with error handling    |
| `exuse`         | Attach router to Express app                            |
| `rroute`        | Router route declaration                                |
| `exrouter`      | Express router file template                            |
| `connectdb`     | Async MongoDB connection function                       |
| `exrouteparam`  | Route with URL params and error handling                |
| `exreq`         | Access `req.query` and `req.body` with validation      |
| `json200`       | JSON response with status 200 OK                        |
| `json201`       | JSON response with status 201 Created                   |
| `json400`       | JSON response with status 400 Bad Request               |
| `json401`       | JSON response with status 401 Unauthorized              |
| `json403`       | JSON response with status 403 Forbidden                 |
| `json404`       | JSON response with status 404 Not Found                 |
| `json500`       | JSON response with status 500 Internal Server Error     |
| `sendtxt`       | Plain text response with status                          |
| `redirect`      | Redirect response with status and URL                    |
| `download`      | File download response with error handling              |
| `mschemaMethod` | Add method to Mongoose schema                            |
| `mschemaVirtual`| Add virtual property to Mongoose schema                  |
| `mschemaPre`    | Add pre-hook with async error handling                   |
| `mschemaIndex`  | Add index to Mongoose schema                             |

---

## 📖 Usage

1. Open a `.js` or `.ts` file in VSCode.
2. Start typing the snippet prefix, e.g. `exindex`, `json404`, or `mschemaMethod`.
3. Press `Tab` or `Enter` to expand the snippet.
4. Use `Tab` to navigate between snippet placeholders.

---

## 🤝 Contributing

Feel free to open issues or submit pull requests for new snippets, improvements, or bug fixes!

---

## 📄 License

MIT License © 2025

---
