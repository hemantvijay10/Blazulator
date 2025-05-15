Blazulator

Blazulator is a simple web-based calculator built with Blazor that lets you enter arithmetic expressions via on-screen buttons and see results in real time. This project is my first foray into Blazor—while I know there’s room for improvement, it was a great way to start experimenting with components, event callbacks, and dynamic rendering.

Features:

1. Clickable numeric and operator buttons to build expressions
2. Live display of the current expression as you type
3. Real-time computation of +, -, *, /, and parentheses
4. Error handling for invalid input and divide-by-zero
5. Responsive layout with Bootstrap styling

Notes & Future Improvements:

1. The expression evaluator uses DataTable.Compute for simplicity; a custom parser would be safer and more flexible.
2. Keyboard support, unit tests, and improved error messages are planned next.
3. CSS spacing and accessibility can be further refined.

Acknowledgements: This project was built as I’m learning Blazor. Thanks to the following course for providing a solid foundation.

Blazor Deep Dive - From Beginner to Advanced in .NET 8
https://www.udemy.com/course/blazor-deep-dive-from-beginner-to-advanced/?couponCode=CP130525BRGB
