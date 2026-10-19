# Mycelium Starter

**TL;DR:** This repo holds an untouched Angular 21 starter project, exactly as the Angular CLI generates it, with nothing added. Nobody uses it, and its intended purpose (perhaps a template for new Mycelium apps) is not written down anywhere.

## What it is

One commit, on 2026-05-15: the output of `ng new` for Angular 21.2. The only screen is the CLI's
placeholder page and the route list is empty. There is no Firebase config, no deploy workflow and
no `package-lock.json`.

## What's in here

| Path | What it is |
|---|---|
| `src/app/` | The CLI starter component and empty routes. |
| `angular.json`, `package.json`, `tsconfig*.json` | Angular 21 project `mycelium-starter`, Vitest for tests. |
| `.vscode/` | Editor settings from the CLI. |

## Run it

```bash
npm install
ng build
```

## Status

Dormant. 1 commit, 2026-05-15; nothing since.
