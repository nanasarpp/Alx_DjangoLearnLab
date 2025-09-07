from bookshelf.models import Book

# Retrieve the book you want to delete
book = Book.objects.get(id=1)

# Delete it
book.delete()