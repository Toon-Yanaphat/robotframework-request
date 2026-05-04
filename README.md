# Robot Framework Request Action

This action runs Robot Framework tests using the [robotframework-request](https://github.com/Marketionist/robotframework-requests) library inside a Docker container.

## Example usage

```yaml
robot_test:
  runs-on: ubuntu-latest
  name: Run Robot Framework API Tests
  steps:
    - name: Checkout
      uses: actions/checkout@v2
    - name: Run Robot Framework API Tests
      uses: Toon-Yanaphat/robotframework-request@v1.0.0
      with:
```
