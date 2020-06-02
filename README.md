# Ngrxbuild

Repro instructions:

- yarn
- yarn nx build router-store --with-deps
- Open `dist/modules/router-store/actions.d.ts` and note the relative path imports instead of what should be an `@ngrx/store` import