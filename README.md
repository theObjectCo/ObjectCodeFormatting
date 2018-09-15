# ObjectCodeFormatting
Fake repo showing the coding practices at Object.

## ObjectExamples Solution
This is an example solution with 3 projects.
Please always structure the solution with clearly distinguished libraries. The distinction has to be made also based on the dependencies of each library.

### ObjectExamples.Core Project

The ground-most library with as few references as necessary. Used by other Projects in the Solution.

### ObjectExamples.Common Project

Helper classes to transfer the data from Core to UserInterface. Might not be necessary when working with a single user interface project.

### ObjectExamples.UserInterface Project

This Project references the Core and the Common libraries. The only part seen and used by the end-user.

