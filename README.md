1. As a user, I can create a new book so that I can to the existing collection

What URL or URLs should we use to create this feature?

GET '/books/new' #=> I should see a form to create a new book
POST '/books' #=> creates a new book


1. Show the user the form
2. When they submit the form, create a new book
3. Redirect them someplace else 
