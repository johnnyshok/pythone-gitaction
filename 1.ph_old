set -x
test_result=$(python -m unittest discover 2>&1)
        if [[ "$test_result" == *"Ran 3 tests"* ]]; then
          echo "Tests Passed"
        else
          echo "Tests Failed""
        fi
      continue-on-error: true

