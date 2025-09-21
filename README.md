# CompanyDB

This project contains SQL code to create a simple company database.

## Database
- **Name:** `CompanyDB`

## Tables
1. **Departments**  
   - Stores department information.  
   - `department_id` is the primary key.  

2. **Employees**  
   - Stores employee details.  
   - Linked to `Departments` using `department_id` as a foreign key.  

3. **Projects**  
   - Stores project details.  
   - Each project has a unique `project_id`.  

4. **EmployeeProjects**  
   - Junction table for the many-to-many relationship between `Employees` and `Projects`.  
   - Uses a composite primary key (`employee_id`, `project_id`).  

## Relationships
- One department can have many employees.  
- Employees can work on many projects.  
- Projects can have many employees.  

