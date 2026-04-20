# agent-runner-sandbox

Sandbox repo for agent-runner integration tests.

## Scenario: calculator service

A minimal Python calculator with stub functions. Used to validate that the
agent-runner pipeline can receive a task, implement code, and commit the result.

## Running tests

```bash
python3 -m pytest src/test_calculator.py -v
```
