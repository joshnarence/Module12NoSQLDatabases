Part 1:
Import the information offered by the businesses.from your Terminal, a json file. Give the collection locations and the database, uk_food, a name. In a markdown cell in your notebook, paste the text that you used to import your data from your Terminal.

Import the required libraries into your notebook: Pretty Print (pprint) and PyMongo.

The Mongo Client object should be created.

Verify that the database was built and the data loaded correctly.

List each MongoDB database you currently use. Check to see if uk_food is listed.

To confirm that the institutions are present, list the collection(s) in the database.

Using find_one and pprint, locate and display one document from the establishment's collection.

To make the establishments collection ready for use, assign it to a variable.

Part 2:

For this portion of the challenge, use NoSQL_setup_starter.ipynb.

Before you run any queries or analyses for the magazine editors, there are some database changes they have asked. Make the following adjustments to the venue's collection:

In Greenwich, a new and fascinating halal restaurant has debuted, although it hasn't been reviewed yet.

Look up the "Restaurant/Cafe/Canteen" BusinessTypeID and only return the BusinessTypeID and BusinessType fields.

Add the BusinessTypeID you discovered to the newly opened restaurant.

Check how many documents contain the Dover Local Authority because the publication is not interested in any Dover establishments. After that, delete any establishments that are part of the Dover Local Authority from the database and verify that they were 

destroyed by counting the number of records.

When they should have been recorded as numbers, some of the number values are instead stored as strings.

To convert latitude and longitude to decimal numbers, use update_many.

To convert RatingValue to integer values, use update_many.
