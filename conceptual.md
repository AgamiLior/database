### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
A: It is an advanced database managment system, it is supporting SQL and JSON.
- What is the difference between SQL and PostgreSQL?
A: PostgreSQL is and advanced database which provide support to different functions of SQL
- In `psql`, how do you connect to a database?
A: \c "Database Name"
- What is the difference between `HAVING` and `WHERE`?
A: HAVING is used to filter rows of data after specific filter has been used, WHERE is used before.
- What is the difference between an `INNER` and `OUTER` join?
A: INNER join refers to the common data between two tables where OUTER join return the full data from one table and the common from the other (or both).
- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
A: LEFT OUTER returns data from the left table and the common from the right, where RIGHT OUTER doing exactly the opposit.
- What is an ORM? What do they do?
A: They are techniques for converting data between incompatible types systems using object oriented programming languages.
- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
A: HTTP requests using AJAX is done through the browser via JavaScript. It may actually be faster as it doesn't need flask. Info is then stored in JavaScript.
   On the other hand, using a server side library like "requests" makes it easier to store data in a database on your computer.
- What is CSRF? What is the purpose of the CSRF token?
A: It is a random token that is used to prevent attacks, The use of the CSRF is to secure application by giving a unique token per user.
- What is the purpose of `form.hidden_tag()`?
A: The form. hidden_tag() template argument generates a hidden field that includes a token that is used to protect the form against CSRF attacks.