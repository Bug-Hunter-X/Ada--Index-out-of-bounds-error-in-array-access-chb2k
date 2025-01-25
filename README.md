# Ada Index Out of Bounds Example

This repository demonstrates a common error in Ada programming: accessing an array element using an index that is out of bounds.  The example code attempts to write to an element beyond the defined range of the array, leading to a `Constraint_Error` exception.

The solution demonstrates how to prevent this by adding checks to ensure the index is within the valid range before accessing the array element.  Always validate your array indices before accessing them to avoid runtime errors.  Ada's strong typing helps catch many such errors at compile time, but this kind of error is typically only detectable at runtime.