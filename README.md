# typescript-eslint-test

## Repro Steps
```
npm install
npm run lint (works fine)

git clean -xdf
npm install -g pnpm
pnpm install
npm run lint (fails)
```
