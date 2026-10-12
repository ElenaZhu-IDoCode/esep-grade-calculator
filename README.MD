# ESEP Grade Calculator

This library is a simple utility to calculate your grades. The program takes the summation of three categories of assignments, 'assignments', 'exams', and 'essays', then multiplies it with a general assignment weight. This numerical weight is then converted into a letter grade scale, where A >= 90, B >= 80, C >= 70, D >= 60, and F < 60

Runtime requirements:
Golang 1.24+

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