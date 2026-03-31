# KPI Brief — Levant Tech Solutions

## KPI 1: [Name]

**Definition:**
**Current value:**
**Interpretation:**

## KPI 2: [Name]

**Definition:**
**Current value:**
**Interpretation:**

## KPI 3: [Name]

**Definition:**
**Current value:**
**Interpretation:**
# KPI Brief — Levant Tech Solutions

## 1. Department Salary Expenditure
**Definition:** Total salary expenditure per department using `SUM(employees.salary)` grouped by `department_id`.  
**Current value:** Add the actual Q2 output.  
**Interpretation:** This shows which departments consume the largest share of payroll cost.

## 2. Highest-Paid Employee per Department
**Definition:** Highest-paid employee in each department using `ROW_NUMBER()` partitioned by `department_id`.  
**Current value:** Add the actual Q3 output.  
**Interpretation:** This identifies the salary leader in each department.

## 3. Project Staffing Ratio
**Definition:** Number of assigned employees per project from `project_assignments`.  
**Current value:** Add values from Q4.  
**Interpretation:** This shows whether projects are lightly or heavily staffed.

## 4. Employee Utilization Rate
**Definition:** Percentage of employees assigned to at least one project.  
**Current value:** Calculate as `(distinct assigned employees / total employees) * 100`.  
**Interpretation:** This measures workforce utilization across projects.

## 5. Above-Average Department Salary Index
**Definition:** Departments whose average salary is greater than the company-wide average salary.  
**Current value:** Add the departments returned by Q5.  
**Interpretation:** This highlights departments with above-average compensation patterns.