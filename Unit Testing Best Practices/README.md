# Introduction to unit test
-------------
1. Ensure that the program works as expected and under any conditions.
2. The software has not been tested, and cannot be trusted.
3. The skill of writing Unit Testing is among the most in-demand skills in the market
4. A programmer who can test his code is better than one who does not know it
---------------------------------------------------------
## What Unit Testing Is?
It is the tests that we write in order to verify that the software units that we write perform as they should be

````
Tests that do these things add value.  They should be part of your general approach to code quality.  They just don’t fall under the heading of unit tests.
````
------------------------------------------------------------------

## Anatomy of a Unit Test
- CalculatorTests  ===>It gets an attribute called “TestClass” to tell Visual Studio’s default test runner and framework, MSTest, that this class contains unit tests.
- Adding_4_And_3_Should_Return_7  ===>  We want to name our test methods in a very descriptive way that indicates our hypothesis as to what inputs should create what outputs
- Assert.AreEqual  ===>Microsoft supplies a UnitTesting namespace with this Assert class in it.  

 ------------------------------

1. Arrange, Act, Assert
2. One Assert Per Test Method
`````
But, remember, hypothesis, experiment.
`````
3. Keep It Short, Sweet, and Visible
