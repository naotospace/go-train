# 1st step
https://tutorialedge.net/golang/intro-testing-in-go/

```bash
go test
PASS
ok      _/go_train/intro_testing  0.367s

go test -v
=== RUN   TestCalculate
--- PASS: TestCalculate (0.00s)
=== RUN   TestTableCalculate
--- PASS: TestTableCalculate (0.00s)
PASS
ok      _/go_train/intro_testing  0.093s

go test -cover
PASS
coverage: 66.7% of statements
ok      _/go_train/intro_testing  0.229s

go test -coverprofile=coverage.out
PASS
coverage: 66.7% of statements
ok      _/go_train/intro_testing  0.091s

go tool cover -html=coverage.out
```