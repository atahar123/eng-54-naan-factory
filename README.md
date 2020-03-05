# TDD Naan Factory Exercise

## This exercise is going to bring together a lot of concepts. They are
- Git
- GitHub
- Functions
- TDD
- Seperation of concerns
- DRY code
- DOD

## Installing and running
To run the factory, do the following

```python
import naan_factory
run naan_factory()
```

### TDD - Test Driven Development
1. Write the test
2. Run it, and read the error
3. Code it and make it pass the test

This helps with:
- Stops over engineering
- Maintainable code
- Reduce technical debt
- Goes well with agile and working code
- Errors can be your guide in complex systems

How it works is that we write unit test.

#### Unit Tests
Test single pieces of code like function

++Basics of a test++
Usually has 3 phases.
- Setup phase (know variables)
- Calling of the function / iece of code with known variables
- Asserting for expect output


### User stories for Naan factory
```
#1
As a user, I can use the make_dough with water and flour to make dough

#2
As a user, I can use the bake_dough with dough to get naan.

#3
As a user, I can use the run_factory with water and flour and get naan.

```


