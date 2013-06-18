abcd
====

Always Be Collecting Data

CODING STANDARDS:

Classes - UpperCamelCase
Methods - lowerCamelCase
Variables - lowerCamelCase

No newlines after declaration.
1 newline after relevant blocks.
Visibility modifiers, even when default.

public class A {
  private final String DEFAULT_VAL = "MONKEY!";
  private int age;
  protected CommonObject commonObject;
  
  public A() {}
  
  public A(int a) {
    this.age = a;
  }
  
  public void methodName() {
    return "a value";
  }
}
