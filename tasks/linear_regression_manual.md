### Assignment: linear_regression_manual
#### Date: Deadline: Oct 18, 23:59
#### Points: 3 points
#### Tests: linear_regression_manual_examples

Starting with the
[linear_regression_manual.py](https://github.com/ufal/npfl129/tree/master/labs/01/linear_regression_manual.py)
template, solve a linear regression problem using the algorithm from the lecture
which explicitly computes the matrix inversion. Then compute root mean square
error on the test set.

#### Tests Start: linear_regression_manual_examples
_Note that your results may be slightly different (because of varying floating point arithmetic on your CPU)._
- `python3 linear_regression_manual.py --test_size=0.1`
```
52.38
```
- `python3 linear_regression_manual.py --test_size=0.5`
```
54.58
```
- `python3 linear_regression_manual.py --test_size=0.9`
```
59.46
```
#### Tests End: