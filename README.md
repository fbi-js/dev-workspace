# dev-workspace
Development workspace for fbi

## Environment Setup

```bash
npm i -g pnpm
```

## Steps:

1. `git clone https://github.com/fbi-js/dev-workspace.git`
2. `cd dev-workspace`
3. Clone projects
   1. `git clone https://github.com/fbi-js/fbi.git`
   2. `git clone https://github.com/fbi-js/factory-factory.git`
   3. `git clone https://github.com/fbi-js/factory-node.git`
   4. `git clone https://github.com/fbi-js/factory-web.git`
   5. ...
4. Install Deps: `pnpm i`


## Dev

- fbi
  1. `cd fbi`
  2. `npm run watch`
  3. in the new terminal tab: `npm link`
  4. check: `fbi`
- factory-factory
  1. `cd factory-factory`
  2. `npm run watch`
  3. in the new terminal tab: `fbi link`
  4. check: `fbi ls`
- factory-node / factory-web
  1. `cd factory-node` or `cd factory-web`
  2. `fbi ls`
  3. `fbi b` or `fbi w`
