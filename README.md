# django-form-review1

### Exercise 1
Create a Book model with name, pageNumber, genre, and publishDate attributes. Create an 'all/' endpoint that prints out all entry names and an 'add/' endpoint that adds a book to the database. Once that's complete, create a 'moreThan50/' endpoint that only prints entries with page numbers greater than 50. The index page should only say "Hello".



### Exercise 2
Create a Car model with make, model, and year attributes. Create 2 entries using 2 different methods (admin site and class construtor using an endpoint).

Create an 'all/' endpoint that prints out all entry years, create a new endpoint that only prints entries with years greater than 2010.



<hr>
#### If you need the help:

1. Do Tutorial 1 (Already completed in this exercise)

2. Create a model in your models.py file with the attributes giving in the question

3. Create a route in your URLS and a definition in your views for each endpoint you'll need in the exercise.

4. Print a HttpResponse to each endpoint/route to make sure they work.

5. Start with the first 'all/' route. Get the array of objects from the database through the model. Print all objects in the terminal. This will check to see if you have objects in your array.

6. If you can print them in the terminal, send them to the template page using context.

7. Print the array in your template page using a for loop {% for eachElement in yourArray %}

8. Create a ModelForm and sent it to your template page context. Print the form in the terminal to make sure you called it correctly.

9. Print the form in your context page.

10. Create the if/else page and save the form information.
