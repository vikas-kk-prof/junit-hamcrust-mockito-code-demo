

# Why we need to perform testing

For verify accepted result.



need to write some methods in java programs to test of perform testing before running or deploying application.

there are two type of testing 

1. **Automation testing** - junit, mockito etc. fast in execution, can perform many test, generate report of final results.

2. **Manually testing** - junit, mockito etc.



# What is junit

Junit Framework is used to perform unit testing. 

unit is small chunk of code which need to tested to reduce the chances of failer in application. 

reduce the burdon of developer 

help to verify the code quality.

generate the reports of test before running application.

let us know any connection failer.



# Basic of junit

Requirement of running and writing junit test in application.



put all the testing code in specific folder. 

    code => src/test/java.

    resources => src/test/resouces.



Naming convenstion. 

test method name must have meaning full name and must be suffixed with test.



# features of junit

It provide wide  range of comparison method and annotation 

it generate result final report ofter performing testing.

Allow to perform autmation testing. 



# Test methods

**Text-fixture** -  it is fixed state in a code or fixed set of steps that is used as a percondition and few other sets of steps 



peform single action Before

perform some action **Before** the test

perform the **test**

perform some action **After**

peform single action After



Test method are the method which perform test and these method label with annotation `@Test` 



## Test cases class

countTestCases()  - count total no of executed tests cases.

TestResult createResult() - used to create testResult.

getName() - return the testcase name.

TestResult run() - execute the test which return Testresult object.

setName() - set the name of testcase.

setUp() - this method is used to write resource association.

tearDown() - this method is used to write resource release code.



## TestResult class

addError(Test test, throwable t) - 

addFailure( Test test, throwable t) - 

endTest(Test test)

errorCount()

failureCount()

run()

runCount()





# Annotations

@Test - label the method as test method 

@Before (@BeforeEach) - this method with execute every time before test method

@After (@AfterEach) - this method with execute every time before test method

@Beforeclass  (@BeforeAll) - this method with execute one time before running all tests.

@Afterclass  (@AfterAll) - this method with execute one time After running all tests.

@Ignores  - this used to ignore the Test method.

@Test( timeout = value ) - set the timeout after which method will execute.

@Test( excepted = Exception.class ) - it will handle the exceptions ( check if method is throw any exception of not. )





# Assert class (method)

1. assertEquals( ext, act ) - check the similarity

2. assertFalse( bool. cond.. ) - the condition as false or not.

3. assertNotNull(obj ) - 

4. assertNull( obj ) - 

5. assertTrue() - 

6. fail() - used to fail any test method so that it will throw any assertion error.

7. assertSame() - two object are refer to same class.

8. assertNotSame() - two object are not refer to same class.



# Practical stuff.






