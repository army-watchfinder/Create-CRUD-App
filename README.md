# Create a CRUD App
## What is this?
This repository is a collection of tasks. The aim of these tasks is to measure developer capabilities via a set of instructions that need completing to the best achievable level. Some resources are provided for ease of use, but the bulk of the code will need to be written from scratch using the standard available tools online that an average developer would use on a day-to-day basis (Stackoverflow, blogs, MSDN documentation, etc. - so _not_ friends).

## The tasks
1. First of all, fork this repository and check out the contents. Everything you'll add going forward will need to be pushed to your (forked) remote repository and needs to be in a working state at any given point. 
2. Create a C# MVC page that displays the name, email address and phone number of all people from the JSON file provided (entities.json).
3. Add a button to each row of records that takes you to the details of each person. Starting with the greeting, display all available details of each person. Make sure tags are displayed in a concise manner and the friends' names are also linked to their own details page.
4. Add a button to the details page that lets you delete each record after confirming the user's choice.
5. Add a button that enables the user to edit each record in the app and saves the changes to the data store.

## Considerations
1. The instructions are intentionally left open to interpretation, so that you can apply your best knowledge. It's worth thinking about architectural considerations, potential for future improvement and comments in general.
2. Before you write any code, think: is this the best way of going about it?
3. Have you got unit test coverage of all your methods? Should you have?
4. On deletion, friend references might need to be updated in other records.
5. When editing a person's name, the change might need to be reflected in the friend listing of other records.
6. When editing a record do you want to allow all fields to be edited at the same time or can they be done field-by-field?
7. Is it straightforward to use the app as is or do you need to provide documentation?