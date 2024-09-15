# week2
week 2 assignment
... part 1'1
SELECT first_name, last_name, date_of_birth
FROM patient;
... 1.2

SELECT provider_id, first_name, provider_specialty
FROM providers;

part 2.1
SELECT *
FROM patients
WHERE first_name LIKE "Ab%";
