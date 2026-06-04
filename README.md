# @fleetia/test-utils

Shared React Testing Library and Vitest helpers for Fleetia packages.

## Install

```bash
pnpm add -D @fleetia/test-utils vitest @testing-library/react
```

## Usage

```ts
import { render, screen, fireEvent } from "@fleetia/test-utils";
```

```ts
// vitest.config.ts
export default defineConfig({
  test: {
    setupFiles: ["@fleetia/test-utils/setup"]
  }
});
```
