# C# Fundamentals

**1.** What is the purpose of a `namespace`?

<!-- enter you answer in the space below -->

```
Tells your code how to import that code to use in other places.
```

**2.** What is the difference between a `class` and a `struct`?

<!-- enter you answer in the space below -->

```
struct is a simple version of a class without a lot of the functionality a class brings.
```

**3.** What is the method that returns an instance of a class, yet it has no return type?

<!-- enter you answer in the space below -->

```
constructor
```

## Example 1

```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```

**5.** In the example what is the access modifier of the `Start()` method?

<!-- enter you answer in the space below -->

```
public
```

**6.** In the example what is `string` an indication of?

<!-- enter you answer in the space below -->

```
the type of the value the method will return
```

**7.** In the example what is `abstract` preventing?

<!-- enter you answer in the space below -->

```
prevents instantiation on its own as abstract classes are generally meant to be base classes for other classes
```

**8.** In the example what is the purpose of `virtual`?

<!-- enter you answer in the space below -->

```
classes that inherit this can choose to override the virtual method with their own but don't have to
```

**9.** Name four access modifiers:

<!-- enter you answer in the space below -->

```
public, private, internal, protected
```

**10.** If you set a class or method to private, what can access it?

<!-- enter you answer in the space below -->

```
Only methods within that same scope
```
