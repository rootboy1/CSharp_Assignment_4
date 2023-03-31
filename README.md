# CSharp_Assignment_4


Create the schema named emplyee and the database named employeemaster

Create columns with the names ID, EmpName, Department, IsActive

Install two packages form the Nuget Package manager
Microsoft.EntityFrameworkCore.Tools
MySql.EntityFrameworkCore

Run this code at the end and can change the folder name if you want to otherwise its okay (Like DataObjects) "Scaffold-DbContext "server=localhost;port=3307;user=root;password=root;database=employee;" MySql.EntityFrameworkCore -OutputDir DataObjects -f"

Put this code in the index()
EmployeeContext myEmployeeContext = new EmployeeContext();
var empData = myEmployeeContext.Employeemasters.ToList();

Run this code from Nuget Console. Using breakpoint
