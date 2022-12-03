# RBT | Terminal

A terminal style website powered by [M4TT72 | Terminal](https://term.m4tt72.com).


## why?

Just forfun

## Quick Start

### Using docker (recommended)

```bash
docker run -d \
  --name terminal \
  -p 3000:3000 \
  -v `pwd`/config.json:/data/config.json \
  m4tt72/terminal
```

### Using npm/yarn

1. Install dependencies:

```bash
yarn install
```

2. Build the project:

```bash
yarn build
```

3. Run the server:

```bash
yarn start
```

## Contributing

Please feel free to pull requests or log issues.

Thanks!
