1. Create Employee Request (POST) –
API URL (POST) - http://localhost:8080/employee
JSON request –
{
"empId": 101,
"empName": "Subodh",
"empCity": "Delhi",
"empSalary": 2000
}

JSON Response –
{
"empId": 101,
"empName": "Subodh",
"empCity": "Delhi",
"empSalary": 2000.0
}

2. Get all employee details –
API URL (GET) - http://localhost:8080/employee
{
    "employees": [
        {
            "empId": 101,
            "empName": "Subodh",
            "empCity": "Delhi",
            "empSalary": 2000.0
        },
        {
            "empId": 102,
            "empName": "Subodh",
            "empCity": "Delhi",
            "empSalary": 2000.0
        }
    ]
}

3. Query employee details based on empId –
   API URL (GET) - http://localhost:8080/employee/101
   {
       "empId": 101,
       "empName": "Subodh",
       "empCity": "Delhi",
       "empSalary": 2000.0
   }
