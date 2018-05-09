For testing the [Developer-Facing Display Conventions](https://webassembly.github.io/spec/web-api/index.html#conventions).

To modify `test.was`, assemble with [wabt](https://github.com/webassembly/wabt):
* `wat2wasm test.was -o test-no-names.wasm`
* `wat2wasm test.was --debug-names -o test-with-names.wasm`
