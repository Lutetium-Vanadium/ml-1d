# Machine Learning 1D project

## Project structure

- The main project file is `1d.ipynb`. It contains all the code for all
  the given parts.
- The `ES`/`RU` directories contain all input and output files for the
  respective datasets, including the `test.in`.
- The `EvalScript` directory contains a modified version of the
  `evalResult.py` given in the handout. It has been modified to allow
  calling it within python code and not requiring it to be run through
  the terminal. However, it can still be run as a script.

In addition to the `main` branch, other approaches for part 4 which
exist in other branches. Please check the report for which branch to
use.

## Dependencies

The project uses `python3`, the `numpy` library and `jupyter`. Please
make sure you have all of these installed before running the code.

## Running the code
To run the code, open the `1d.ipynb` file and run all the cells. The
outputs for each of the models labelling `dev.in` will be printed to the
output of the notebook itself. 

To get the scores for the test datasets, while in the root directory of
the project, the following commands can be run.

```shell
python3 ./EvalScript/evalResult.py path/to/gold ./ES/test.p4.out
python3 ./EvalScript/evalResult.py path/to/gold ./RU/test.p4.out
```
