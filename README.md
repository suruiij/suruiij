# airelag

Vite + React app for the lasyja gallery experience.

## Project Structure

```text
src/
  app/            App shell, routing, layout, and global modal host
  components/     Reusable UI components
  components/modals/
                  Portal-based modal components
  hooks/          Shared React hooks
  lib/            Browser clients and external service helpers
  pages/          Route-level screens
  store/          Global Zustand state
  styles/         Global Tailwind/CSS entrypoint
  main.jsx        React entrypoint mounted from index.html
```

Use the `@/` alias for source imports, for example:

```js
import { useAppStore } from '@/store/appStore.js';
```

## Commands

```sh
npm run dev
npm run build
npm run preview
```
