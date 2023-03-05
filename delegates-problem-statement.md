## CSharp Exercise

### Working with Delegates

1. Write a C# program to create a multicast delegate with name `CalculateHandler`. This delegate should hold the reference of 4 different methods - `Add`, `Subtract`, `Multiply` & `Divide`. Each method should have 2 parameters. You have to call these methods from main by using `CalculateHandler` delegate. All 4 methods should perform their respective operations and display the output on console.

2. Write a C# program to solve the above problem by using 4 different `Func` delegates with name `CalculateAdd`, `CalculateSubtract`, `CalculateMutiply` & `CalculateDivide` instead of creating the multicast delegate explicitly. Since we are using the `Func` delegate, this time the methods should return the value rather than printing it on the console.

3. Write a C# program to create a multicast delegate with name `AttendanceLogHandler`. This delegate should hold the reference of 2 methods - `CreateLog` & `MarkAttendance`. Both the methods are taking `EmployeeId` as string parameter. `CreateLog` method is creating a log file with the same name as `EmployeeId` if file not exists. If the log file already exists it should display a message on console as `Log File already exists` whereas `MarkAttendance` is writing the attendance in the file with current system datetime. For example, the log file should have the entry like this - `E2314 has marked the attendance on 16-09-2020 09:30:04`. In main method write the code to take `EmployeeId` as input from user and pass it to `AttedanceLogHandler` delegate. You have to call the methods using delegate.

4. Write a C# program to solve the above problem by using 2 different `Action` delegates with name `LogDelegate` and `AttendanceDelegate` instead of creating the multicast delegate explicitly.
