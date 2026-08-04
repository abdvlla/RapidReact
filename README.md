# RapidReact

RapidReact is a VS Code extension that helps you write React and TypeScript code faster with practical snippets for everyday development.

## Features

RapidReact includes snippets for:

- React components, props, lists, modals, and dropdowns
- React state, effects, forms, fetch patterns, and custom hooks
- React Hook Form and Zod setup helpers
- Common utility functions such as debounce, clipboard, localStorage helpers, and formatting helpers
- Axios request helpers and page templates
- TanStack Query setup, useQuery, and useMutation snippets

## Usage

Open a TypeScript or TSX file and start typing one of the snippet prefixes, for example:

- `rr.state`
- `rr.formpage`
- `rr.usefetch`
- `rr.axios.get`
- `rr.tq.query`

## Development

To build the extension locally:

```bash
npm install
npm run compile
```

## Publishing

Before publishing, update the publisher name in the package manifest and then package the extension:

```bash
npx @vscode/vsce package --no-dependencies
```

## Notes

This is an early version of the extension. More snippets and refinements will be added over time based on feedback and usage.
