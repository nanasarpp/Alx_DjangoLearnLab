 book = Book.objects.get(id=1) 
>>> book.title = "Grief Child"    
>>> book.publication_year = 2000
>>> book.save()