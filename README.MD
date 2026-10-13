# ESEP Grade Calculator

The ESEP Grade Calculator is a simple library written in Go that calculates a student's final course grade based on their assignments, exams, and essays.

The calculator determines the average score for each category, applies the appropriate weights, and converts the resulting numerical grade into a letter grade.

Runtime requirements:
Golang 1.24+

Installation and Setup

1. Clone the repository:
    git clone https://github.com/AaronGibson2/esep-grade-calculator.git
2. Navigate to the project directory:
    cd esep-grade-calculator/grade-calculator
3. Verify that Go is installed and useable version
    go version


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