# shtest

Minimal test harness for bash scripts.

### Usage
`shtest [test suite]`

Similar to `pytest`, `shtest` will run any functions starting with `test_`.

The functions `setUp` and `tearDown`, if defined in the test suite, are run before and after each test.

`shtest` provides functions beginning with `assert` and `expect` for verifying test conditions.
