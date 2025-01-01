# Uninitialized Map Access in Go

This repository demonstrates a common error in Go: accessing an uninitialized map.  Go maps are not automatically initialized; attempting to access or modify an uninitialized map will result in a runtime panic.

The `bug.go` file contains the buggy code.  The `bugSolution.go` file provides a corrected version.

## How to reproduce

1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `go run bug.go` (this will panic)
4. Run `go run bugSolution.go` (this will execute without errors)