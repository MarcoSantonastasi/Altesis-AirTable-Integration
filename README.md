# Altésis-AirTable-Integration
A small project to learn how to use Airtable API (airtable.js) to create and modify a record in a database.

The objective of the exercise is to familiarize with chatting in javacript with a REST API and learn about the ORM model.

Steps:
1) Create a new Airtable record, and get the UUID of said record;
2) Using the UUID from step 1), create a new record in another table that references the first one in its linked field.

Acivity:
1) Populate a <form> to ask the user for the required fields for the new record;
2) Use Airtable.js to create a new record;
3) Use airtable.js to create a second new record with a pefilled field that contains the UUID of the record in step 1).

In this particular case, Airtable internal routine will make sure that the record in step 1) is updatede too, so you do not have to check or expend any effor to verify consistency of the database.

You will need to learn about the [Airtable API](https://airtable.com/api) and not care about the script airtable.js
