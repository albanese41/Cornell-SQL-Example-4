INSERT INTO Employees (first_name, last_name, manager_id)

VALUES (‘John’, ‘Smith’, SELECT manager_id

FROM Managers

WHERE first_name = ‘Mary’ AND last_name = ‘Windsor’);
