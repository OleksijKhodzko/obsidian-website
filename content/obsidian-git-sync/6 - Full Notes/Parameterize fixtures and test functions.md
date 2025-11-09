```python
@pytest.mark.parametrize("test_input, expected", [("3+5", 8), ("2+4", 6)])
def test_eval(test_input, expected):
	assert eval(test_input) == expected
```

To get all combinations of multiple parameterized arguments:
```python
@pytest.mark.parametrized("x", [0, 1])
@pytest.mark.parametrized("y", [0, 1])
def test_foo(x, y):
	pass
```