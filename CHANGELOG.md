## v4.1.0
- `onCatastrophicError` added

## v4.0.0
- `Callback` class addeed.
- When possible, `reference.get()` will return a function delegate instead of a `Reference`.
- `reference.get()` will no longer return inherited properties by default.
- `result` property on `eval` and `evalClosure` has been removed. The result is now just the return
value.
- All `isolated-vm` class prototypes, and most instances are frozen.
- `isolate.cpuTime` and `isolate.wallTime` now return bigints.
- Proxies and accessors are no longer tolerated via `reference.get`, and related functions.