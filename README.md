# UCB-Project-Two
Project 2 Team 15
## A Category DataFrame  and a Subcategory DataFrame are Created
- Use .unique().tolist() to get all the unique categories and subcategories
- Use len() to get the number of distrinct values in the category & subcategory lists
- Use np.arrange() to create numpy arrays from 1-9 for categories and 1-24 for the subcategories
- Use a list comprehension to add "cat" to each category_id and "subcat" to each subcategory_id
- Create the category DataFrame with "category_id" and "category" and subcategory DataFrame with "subcategory_id" and "subcategory"
## A Campaign DataFrame is Created
- Create a Campaign DataFrame with all the necessary columns requested
- Clean up the data by formatting the data types to requested and dropping the unnecessary columns
- Extract the contacts.xlsx Data: the provided code has header = 2, which is incorrect. header = 3 is correct and applied
## A contacts DataFrame is Created
- Iterate through the contact DataFrame to convert each row's JSON-formatted data into a Python dictionary
- Clean up the data by checking the data types and organizing column orders
- Export the DataFrame as a CSV file
- Use regex to extract the four-digit contact ID number and extract the name of the contact
## A Crowdfunding Database is Created
- Create ERD (Entity-Relationship Diagram) to represent the relationships among the entities between the four tables
- The database has the appropriate primary and foreign keys and relationships
- Each CSV file is imported to the correct table
