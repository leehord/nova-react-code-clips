## Version 2.0.0

A major modernisation update bringing all clips in line with current React best practices.

### Breaking Changes

- **Removed all class component snippets** (`rcc`, `rce`, `rcep`, `rcp`, `rpcp`, `rpce`, `rccp`, `rcredux`, `rcreduxp`) — use functional component equivalents instead
- **Removed React Native class component snippets** (`rnc`, `rncs`, `rnce`, `rncredux`) — use functional equivalents instead
- **Removed TypeScript class component snippets** (`tsrcc`, `tsrce`, `tsrpc`, `tsrpce`, `tsrcredux`)
- **Removed class lifecycle method snippets** (`rconst`, `rconc`, `est`, `cdm`, `scu`, `cdup`, `cwun`, `gdsfp`, `gsbu`, `ren`, `sst`, `ssf`, `props`, `state`, `bnd`, `cref`, `cp`, `cs`)
- **Removed `react-test-renderer`** from test scaffolds — replaced with `@testing-library/react` and `@testing-library/react-native`
- **Updated `imrd`** from `react-dom` to `react-dom/client`
- **Updated GraphQL snippets** from deprecated `react-apollo` to `@apollo/client` hooks

### New Snippets

- `croot` — `createRoot` setup for React 18+
- `reb` — Error Boundary component (class still required by React)
- `rlazy` / `rsuspense` — `React.lazy` and `Suspense` code splitting
- `useTransition` / `useDeferredValue` — React 18 concurrent hooks
- `useId` / `useSyncExternalStore` / `useInsertionEffect` — React 18 hooks
- `useHook` (`use()`) / `useOptimistic` / `useActionState` / `useFormStatus` — React 19 hooks
- `imbro` / `imbrna` / `imrnav` / `imrpar` / `imrloc` / `imrsp` — React Router v6 imports
- `useNavigate` / `useParams` / `useLocation` / `useSearchParams` — React Router v6 hooks
- `tqprovider` / `imtq` / `tqquery` / `tqmutation` — TanStack Query (`@tanstack/react-query`)
- `imswr` / `swr` / `swrf` — SWR data fetching

### Other Changes

- Removed `import React` from all functional component snippets (not needed since React 17 JSX transform)
- Updated all hook imports to use named imports without `React,` prefix
- Updated `useDispatch` to remove erroneous argument
- Updated `useMemo` and `useCallback` to use assignment pattern with proper tabstops
- Updated `reduxSlice` to use named tabstops
- Updated Router snippets to React Router v6 (`Routes` replaces `Switch`, `Outlet`, `Navigate`)
- Fixed `rnfe` which had a hardcoded filename

## Version 1.0.2

Typo fix for 'rafce' clip name courtesy of [@dlbnco](https://github.com/dlbnco)

## Version 1.0.1

Some minor fixes courtesy of [@Pitchoune](https://github.com/Pitchoune):

- Added 2 missing commands listed in readme
- Added missing existing commands in readme
- Fixed 'typeof' command (spelled tpyeof)

## Version 1.0

Initial release
