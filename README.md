# Bug reproduction

Check out the `dist` folder (alternatively, `pnpm run build` and then `pnpm run preview`):

The svelte component's styles are generated in the `assets`
directory but not linked in the resulting HTML, resulting in unstyled component elements.

