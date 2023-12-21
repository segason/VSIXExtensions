# TestMethod AAASnippets
## Summary
This extension allows you to generate a skeleton for test methods for the MSTest testing framework with the AAA comments already in the body of the method. This may save you time while writing unit tests and prevent you from wasting time rewriting the AAA comments every time.

## How to use
### Create TestMethod method with AAA
- `testmethod` [TAB]

```
[TestMethod]
public void TestMethod()
{
    // Arrange

    // Act

    // Assert
}
```


### Create async TestMethod method with AAA
- `asynctestmethod` [TAB]

```
[TestMethod]
public async Task TestMethodAsync()
{
    // Arrange

    // Act

    // Assert
}
```
