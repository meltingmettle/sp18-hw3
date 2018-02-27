## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?

The 'nil' argument shows the placeholder when the tag is nil and removes it when the value is no longer nil.


2. Go to `localhost:3000/teachers` in your browser; why does this not work?
There is no route for a request called "teachers"

3. What type of request did your browser just perform?
A GET request.

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
http://localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?
The route creates the form which allows the form to navigate to the page.
