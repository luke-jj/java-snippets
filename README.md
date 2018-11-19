# Java Snippets

## Clear Screen On Unix Compatible Shells

```java
  public void clearScreen() {
    System.out.print("\033[H\033[2J");
  }
```
