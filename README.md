# Auto-Car-


class Employee:
    emp_count = 0
    def __init__(self, name, salary):
        self.name = name
        self.salary = salary
        Employee.emp_count += 1

    def display_count(self):
            print('display_count', Employee.emp_count)

    def display_employee(self):
            print('Name:', self.name, ', Salary: ', self.salary)

emp_1 = Employee('Zoya', 1000)
emp_2 = Employee('George', 1700)
emp_3 = Employee('Dmitry', 2500)

emp_1.display_employee()
emp_2.display_employee()
emp_3.display_employee()

employee_count = Employee.emp_count
print('employee_count:', employee_count)

emp_1.age  ()
