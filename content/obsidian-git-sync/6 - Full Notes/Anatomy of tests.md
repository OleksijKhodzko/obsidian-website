tags: [[Testing]]
links: [[pytest]]

Test can be broken i 4 parts:
1. [[#Arrange]]
2. [[#Act]]
3. [[#Assert]]
4. [[#Cleanup]]

### Arrange 
Prearrange everything: set up variables, services, connect databases, e.t.c.

### Act
Execute the code and gather results

### Assert
Check the results of the execution and their relevance to the expectations.

### Cleanup
Clean everything up not to affect the rest of the tests.


