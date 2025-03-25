# Int-vs-Double-CSharp

## Description  
This repository explains the difference between the `int` and `double` data types in C#. It highlights their memory usage, purpose, and when to use each.  

## Difference Between `int` and `double`  

In C#, `int` (integer) is a data type used to store whole numbers, both positive and negative, without decimal points. It takes up **4 bytes (32 bits)** of memory and is commonly used for variables that require whole-number values, such as counting objects or tracking a person’s age.  

For example, when counting the number of students in a class or the number of apples in a basket, an `int` is ideal because fractional values are not needed.  

On the other hand, `double` is a floating-point data type that occupies **8 bytes (64 bits)** of memory and is used to store numbers with decimal points. It is useful in situations where precision is required, such as financial transactions, scientific measurements, or academic grading systems.  

For instance, when calculating a product’s price, recording a student's GPA, or measuring a person’s height, `double` is preferable because it can store values like `25.99`, 13.75`, or `1.9`.  

## Example Usage  

### Example of `int` Usage:  
```csharp
int numberOfStudents = 25;
Console.WriteLine("Total students: " + numberOfStudents);
```

### Example of `double` Usage:  
```csharp
double productPrice = 25.99;
Console.WriteLine("Product price: " + productPrice);

## Conclusion  
The `int` data type is best for whole numbers where precision is not required, while `double` is better for numbers with decimal points where accuracy is important. Choosing the right data type ensures efficient memory usage and prevents unnecessary errors in calculations.  

