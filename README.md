# Go Deadlock Example

This repository demonstrates a common deadlock scenario in Go programs involving channels and wait groups.  The `bug.go` file contains code that deadlocks. The `bugSolution.go` file provides a corrected version.

The issue stems from improper handling of goroutine termination and channel closure, leading to a situation where goroutines wait indefinitely for each other.  Understanding this pattern helps prevent similar deadlocks in concurrent Go programs.
