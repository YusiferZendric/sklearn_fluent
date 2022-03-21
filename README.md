# sklearn_fluent
Just provide x and y list and there you have it the Mathemtical function + accuracy based on the x and y list.

## You can get it at [sklearn_fluent](https://pypi.org/project/sklearn-fluent/0.0.1/)
or 
``` bash
pip install sklearn_fluent
```

# Usage
``` python
from sklearn_fluent import fluent_it
# for linear_regression
xlist = [4,123,21,312,313]
ylist = [21,23,124,12,31]
fluent_it(xlist,ylist,linearreg=True)
```
Result:
```bash
>> 'function: -0.1494a + 65.3014'
```
``` python
# for multi_regression
xlist = [[432,423,42],[14,213,32],[2432,23,2]]
ylist = [5,234,212]
fluent_it(xlisst,ylist,linearreg=False)
```
Result: 
```bash
>> 'function: -0.0824a + -0.9238b + -0.0571c + 433.7416'
```
