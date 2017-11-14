# Django_basics
project 
following URL either display a simple HttpResponse or redirect to a different URL for the following apps
blogs app
/ - display "placeholder to later display all the list of blogs" via HttpResponse. handled by a method named 'index'.
/new - display "placeholder to display a new form to create a new blog" via HttpResponse. handled by a method named 'new'.
/create - Have this be handled by a method named 'create'.  url redirect to /.
/{{number}} - display 'placeholder to display blog {{number}}'.  For example /15 should display a message 'placeholder to display blog 15'.  Have this be handled by a method named 'show'.
/{{number}}/edit - display 'placeholder to edit blog {{number}}.  handled by a method named 'edit'.
/{{number}}/delete - Have this be handled by a method named 'destroy'. url redirect to /. 
