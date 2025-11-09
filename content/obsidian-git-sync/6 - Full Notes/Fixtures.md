tags: [[Testing]], [[pytest]]

A **test fixture** is a device used to consistently test some item, device, or
piece of software. Test fixtures are used in the testing of electronics, 
software and physical devices.

Fixtures define the steps and data that constitute the [[Anatomy of tests#Arrange|arrange]] phase of a test.

### In pytest

In pytest fixtures are functions, defined to execute the arrange phase.

The services, state, or other operating environments set up by fixtures are accessed by test functions through arguments. For each fixture used by a test function there is typically a parameter (named after the fixture) in the test function’s definition.

Use @pytest.fixture decorator to define a fixture. 