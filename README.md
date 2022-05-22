# Studybud website learning note
## Comparsion with Flask

* similar points: 
  * jinja2: Passing parameter into html is same
  * model to define the table
  * use decorator to secrete the login 

* not similar points:
  * MVT vs MVC
  * ORM vs Sqlachemy  
  * Encrypto: Django admin mode auto takes care of the password encrypto. In Flask, we have to define the hash encrypto by ourselves.
  * Define login: Django is more compact and logical by using Sqlite. Flask need more code to do the same things by using Sqlalchemy.
  * Default register form
