Database normalization is a standardized process of organizing data/database tables into a more structured form.

The main reasons to normalize a database is to minimize duplicate data, avoid data modification issues, and to simplify queries.

Database tables are best suited to have one, and only one organizational purpose. E.G., ONLY employee data, ONLY customer data, ONLY office location data, etc.

Having duplicate data increases the likelihood that there will be issues with updating and deleting table entries, and searching/sorting data. Data needs to be separated into different tables such that all the data operates as independently as possible.

Tables should be united by a primary key; different, but related tables can be united by a foreign key.

Apparently, we should avoid using null like the plague. Use something else, such as zero.

There are all kinds of joins, and we have a handy visual reference now to come back to. I wonder, how often are we going to need to join pre-existing data tables, and normalize the data?