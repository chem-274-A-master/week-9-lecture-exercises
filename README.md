# Week 9 Lecture Exercises

Complete the task described in each `main.cpp`. The six exercises practice
standard algorithms (`copy`, `fill`, `sort`, `find`, and predicates), function
objects, file input, and string streams. Use a C++17 compiler such as `g++`.

From the repository root, run one test at a time:

```sh
bash CCopyFill/run_test.sh
bash CFilestreams/run_test.sh
bash CFind/run_test.sh
bash CFunctors/run_test.sh
bash CSort/run_test.sh
bash CStringstreams/run_test.sh
```

The scripts work from any directory and build in temporary directories. A
passing test prints `SUCCESS`. `CFilestreams` reads its provided
`test_data.xyz` from the exercise directory. To run all six tests and see the
same six-point summary as GitHub Actions, run:

```sh
python3 .github/scripts/grade.py
```

The grader writes `grading-results.json` locally. Unfinished starters are
expected to fail. Submit changes to `main.cpp` files only; tests and grading
configuration are part of the assignment.
