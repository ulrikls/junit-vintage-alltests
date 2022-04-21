This project contains a JUnit4 test and a JUnit3 test.

When using JUnit Platform (JUnit 5) the JUnit 3 test is not executed.

Any of these changes will execute the JUnit 3 test:
* Switching to JUnit 4 - `useJUnit()` instead of `useJUnitPlatform()`.
* Changing the name of the test from `JUnit 3 style test` to `testSomeLibraryMethodReturnsTrue`.
* Removing the `@RunWith(AllTests.class)` annotation and the `suite()` method.
