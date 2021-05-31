# Assume we want to retrieve a single object for a Django model called Attendee with primary key = 7. Write down the query used in Django ORM for the same.

```
from django.db.models import Attendee

query = Attendee.objects.get(pk=7)

print(query)
```
