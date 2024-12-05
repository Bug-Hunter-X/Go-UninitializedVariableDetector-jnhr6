# Uninitialized Variable Bug in Go
This repository demonstrates a common error in Go: using an uninitialized variable.  The `bug.go` file contains code that attempts to use an integer variable before assigning it a value.  The `bugSolution.go` file provides the corrected version.

## How to Reproduce
1. Clone the repository.
2. Navigate to the repository directory.
3. Run `go run bug.go` (this will result in a compiler error).
4. Run `go run bugSolution.go` (this will execute successfully).