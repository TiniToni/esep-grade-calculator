# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Uses golang as the main programming language. Also uses the esepunittests package.

File Summary:
a.    README.MD: Tells how to run the unit tests with and without code coverage.
b.    go.mod: Where to import grade-calculator and the minimum version of Golang required.
c.    grade_calculator.go: sets up the grade calculator struct and the functions needed to modify or use the stucts created from it.
d.    grade_calculator_test.go: test cases for the grade calculator.

Runtime requirements:
Install Golang onto the system with: https://go.dev/dl/
Golang 1.24+

Tests if the given grades average together into the desired grade in the test.
Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
