# c-project-extension

This is the extension for the C group project as part of our first year final project. Credits go to my team: Soham Gadgil, Yash Patel and Devin Thomas.

This is PANDR - Persons Affected by Natural Disasters Reunification. The application helps missings peoples from natural disasters be reunited with family and friends. 


The way that this application works is that there are 2 interfaces, one to the family/friends and the other to the hospital/ward. 

The hospital would upload an image of the missing person with their name (if known) and a brief physical description. This gets added to the database.

Any family looking to find their lost loved one would send a request to the database with an image, name and brief physical description. The image gets matched by an image matching algorithm, and by NLP the descriptions are matched. The highest percentage match across the two are returned to the family.

This was made entirely in C.
