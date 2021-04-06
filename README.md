## About this project

1. **To create functions**
```bash
# Creates a function and a unit test with mocha
sls create function --function functionName --handler src/functions/functionName.functionName --path src/tests/
```

2. **To run tests**
```bash
mocha src/tests
```