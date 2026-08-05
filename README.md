# RapidReact

RapidReact is a VS Code extension for React and TypeScript developers who want to move faster without leaving their editor. It adds practical snippets for common UI patterns, forms, hooks, utilities, API helpers, and data-fetching setups.

## Why RapidReact?

- Generate boilerplate in seconds
- Stay in the flow while building React applications
- Reduce repetitive typing for everyday patterns
- Keep your code consistent with typed, production-friendly starters

## Features

### React patterns

- `rr.state` for `useState`
- `rr.effect` for `useEffect`
- `rr.props` for typed props components
- `rr.list` for list rendering
- `rr.form` and `rr.formpage` for form scaffolding
- `rr.fetch`, `rr.fetchpage`, and `rr.usefetch` for fetch-based data flows
- `rr.modal` and `rr.dropdown` for common UI building blocks

### Forms and validation

- `rr.rhf` for React Hook Form setup
- `rr.zod` for Zod schemas
- `rr.rhf.zod` for React Hook Form + Zod together

### Utilities

- `rr.classnames`, `rr.debounce`, `rr.clipboard`, `rr.dateformat`, `rr.randomid`, `rr.storage`, `rr.errormessage`, `rr.numberformat`, `rr.sleep`, and `rr.safeparse`

### API and data fetching

- `rr.axios.get`, `rr.axios.post`, `rr.axios.instance`, and `rr.axios.interceptor`
- `rr.axios.getpage` and `rr.axios.postpage`
- `rr.tq.client`, `rr.tq.query`, `rr.tq.mutation`, and `rr.tq.querypage`

## Installation

Install the extension from the VS Code Marketplace and open any TypeScript or TSX file.

## Usage

Start typing any of the snippet prefixes below:

- `rr.state`
- `rr.formpage`
- `rr.usefetch`
- `rr.axios.get`
- `rr.tq.query`

## Preview

![Create a props component and add useState and useEffect](docs/gifs/rr.propseffectstate.gif)

![Generate an entire fetch page](docs/gifs/rr.fetchpage.gif)

![Map through a list quickly](docs/gifs/rr.list.gif)

![Create an axios instance and interceptor](docs/gifs/rr.axios.gif)

![Generate an entire Tanstack Query page](docs/gifs/rr.tq.querypage.gif)

## Contributing

Contributions are welcome, but changes are reviewed before they are merged. Please read [CONTRIBUTING.md](CONTRIBUTING.md) for the workflow and review process.

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

## License

MIT
