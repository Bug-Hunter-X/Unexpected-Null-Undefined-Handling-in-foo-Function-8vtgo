# Unexpected Null/Undefined Handling in foo Function

This repository demonstrates a common JavaScript bug related to unexpected behavior when null or undefined values are passed as arguments to a function.  The `foo` function demonstrates this issue. The solution showcases a robust approach to handle these cases.

## Bug Description
The `foo` function fails to handle null or undefined values gracefully, which could lead to unexpected errors or incorrect results depending on the internal logic of the function.

## Bug Solution
The provided solution uses explicit checks for null and undefined values to handle these cases appropriately.  This helps to prevent unexpected behavior and improve the robustness of the function.