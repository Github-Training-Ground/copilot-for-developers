# Refactoring Java codes through Copilot chat in Visual Studio Code

**Refactoring** is an important part of software development. It is a process of changing the internal structure of the code without changing its external behavior. Refactoring is a key to keep your code clean and maintainable. However, refactoring is not easy. It requires a lot of effort and time to refactor a code. Copilot can help you to refactor your code by providing you with a lot of suggestions. In this lab, you will learn how to use Copilot to refactor your Java code.

And most development teams are going work with existing code base. That means that Copilot also needs to work around existing code base.


## start with a simple Java class to add the numbers 0 to 100

```
public class CopilotRefactoring {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }

    public static int addNumbers(int n) {
        int sum = 0;
        for (int i = 0; i <= n; i++) {
            sum += i;
        }
        return sum;
    }
}
```


