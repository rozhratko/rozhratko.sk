# rozhratko.sk

This is the source code of the company's website, [rozhratko.sk](https://rozhratko.sk),
built using Vite and Vue.

## Development

### Install dependencies

```bash
bun install
```

### Run development server

```bash
bun run dev
```

## Favicon

`public/favicon.svg` is the source of the icon. Then, generate the `favicon.ico` file using:

```bash
convert favicon.svg -define icon:auto-resize=128,64,48,32,16 favicon.ico
```
