# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Runtime requirements:
Golang 1.24+
To install go, download from the official go website and then add it to your path in environment variables

Files in repository:
go.mod: Go module files with dependencies.
grade_calculator.go: Contains the code for the grade calculator, instantiation, addGrade, calculateNumericalGrade, etc.
grade_calculator_test.go: Unit tests for grade calculation and numerical conversion

Run unit tests:
```
cd grade-calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade-calculator/
go test -coverprofile=coverage.txt ./...
```
The purpose of coverage is to provide robust documentation to which tests failed in a coverage.txt file