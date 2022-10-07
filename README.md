# Python_numpy_practice

**1- Type Coercion**<br />
Numpy arrays cannot contain elements with different types. If you try to build such a list, some of the elements' types are changed to end up with a     homogeneous list. 

Snippet:
np.array([True, 1, 2]) + np.array([3, 4, False])
Result:
array([4, 5, 2])

As numpy forces array has single type of values so it's speed is much X faster than normal python arrays.
