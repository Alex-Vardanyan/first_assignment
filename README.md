# first_assignment
**Modifying IL code to change the entry point using csc, ildasm and ilasm:**
After compiling the assignment.cs into assignment.exe using csc.exe and disassembling it using ildasm, I dumped the IL code (assignment_dump.il). After changing the .entrypoint from Main function to SomeFunc and saving it, I ran ilasm and assembled it into a PE file (assignment_dump.exe).
