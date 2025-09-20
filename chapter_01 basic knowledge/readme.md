### comment description
```
//! Math Moudle  <-------- This is a math module for basic arithmetic operations
//!
/// # add function <-------- This function adds two numbers
/// # Example
/// ```
/// let sum = math::add(5, 3);
/// assert_eq!(sum, 8);
/// ```
pub fn add(a: i32, b: i32) -> i32 {
    a + b
}
```

### Name Conventions

| item                | Convention           | Example      |
|---------------------|----------------------|--------------|
| Crate               | snake_case           | `my_crate`   |
| Types               | UpperCamelCase       | `MyStruct`, `MyEnum` |
| Traits              | UpperCamelCase       | `MyTrait`    |
| Enums               | UpperCamelCase       | `MyEnum`     |
| Functions           | snake_case           | `my_function` |
| Method              | snake_case           | `my_variable` |
| Constructor         | UpperCamelCase       | `MyStruct::new()` |
| Conversion function | from_other_type      |  |
| Macro               | snake_case!          | `println!`   |
| Local variable      | snake_case           |          |
| Static variable     | SCREAMING_SNAKE_CASE | `MAX_SIZE`   |
| Constant            | SCREAMING_SNAKE_CASE | `PI`         |
| Type parameter      | UpperCamelCase       | `T`, `U`     |
| Lifetime parameter  | lower case           | `'a`, `'b` |






