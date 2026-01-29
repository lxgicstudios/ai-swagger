# ai-swagger

[![npm version](https://img.shields.io/npm/v/ai-swagger.svg)](https://www.npmjs.com/package/ai-swagger)
[![npm downloads](https://img.shields.io/npm/dm/ai-swagger.svg)](https://www.npmjs.com/package/ai-swagger)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Generate OpenAPI 3.0 specs from your Express routes. Point it at your routes directory and get a complete Swagger doc.

## Install

```bash
npm install -g ai-swagger
```

## Usage

```bash
npx ai-swagger ./src/routes/
# Generates openapi.yaml from all route files

npx ai-swagger ./src/routes/users.ts -o docs/api.yaml
# Single file, custom output path
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-o, --output <path>` - Output file path (default: openapi.yaml)

## License

MIT
