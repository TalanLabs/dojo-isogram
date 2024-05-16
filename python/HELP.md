# Help

## Running the tests

We use [pytest][pytest: Getting Started Guide] as our website test runner.
You will need to install `pytest` on your development machine if you want to run tests for the Python track locally.
You should also install the following `pytest` plugins:

- [pytest-cache][pytest-cache]
- [pytest-subtests][pytest-subtests]

Extended information can be found in our website [Python testing guide][Python track tests page].


### Running Tests

To run the included tests, navigate to the folder where the exercise is stored using `cd` in your terminal (_replace `{exercise-folder-location}` below with your path_).
Test files usually end in `_test.py`, and are the same tests that run on the website when a solution is uploaded.

Linux/MacOS
```bash
$ cd {path/to/exercise-folder-location}
```

Windows
```powershell
PS C:\Users\foobar> cd {path\to\exercise-folder-location}
```

<br>

Next, run the `pytest` command in your terminal, replacing `{exercise_test.py}` with the name of the test file:

Linux/MacOS
```bash
$ python3 -m pytest -o markers=task {exercise_test.py}
==================== 7 passed in 0.08s ====================
```

Windows
```powershell
PS C:\Users\foobar> py -m pytest -o markers=task {exercise_test.py}
==================== 7 passed in 0.08s ====================
```

