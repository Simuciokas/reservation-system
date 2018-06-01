###Reservation system includes

##Simple login system
	- Checks for correct usage of inputs such as Name, Surname, Email and Phone number.
	- Uses PHP sessions ($\_SESSION['']) as sessions.
	- Header contains a check for enabled condition doing a query to the database.

##Role system
	- Junior, Controller and Admin roles have different permissions.
	- Admin can edit, add and view everything stored on the website/database such as users and their information and reservations(can't edit) and can do what other roles can
	- Controller can view documents and verify reservations
	- Junior can verify reservations

##Reservation system
	- Check-in and check-out date
	- Stores verified reservations in documents with references to user, room and price at that time.