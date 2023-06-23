Normalize the un-normalized table given below through 1NF, 2NF and 3NF.

**In order to complete this exercise successfully, please keep in mind the following points as you work on the normalization case. Not following all of these instructions may result in lost points on this exercise even if your final set of tables is correct.**

- Normalize the flat table through each of the 1NF, 2NF and 3NF separately and in sequence.
- Make sure that you cover each normalization step (1NF, 2NF, 3NF) separately, explicitly, and in sequence.
- Do not skip any normalization steps.
- In each normalization step, you should only resolve the issue(s) that pertain to the given step. (For example, do not resolve transitive dependencies in 1NF or 2NF, as transitive dependencies are 3NF business.)
- In each step, list all of the tables, including those that do not change in the given step.
- Identify and show primary keys and foreign keys in each step.
- Show the relationships between the tables in each step (by drawing lines/arrows between corresponding PKs and FKs).
- The sample records are for your reference only to help you understand the nature of each field. You should not include them in your work.
- Document your work in MS Excel, MS Word, MS PowerPoint or some other application of your choice that allows inserting and manipulating tables easily. You may want to save the file as a PDF file before submission. Name your file: yourlastname_a5_normalization.pdf, (or ...docx, ...xlsx, ...pptx, depending on the application you use and the resultant file type).


|Field Name|Sample Record|
|---|---|
|Festival Name|	Breaux Bridge Crawfish Festival |
|Festival Description	|This huge food and music festival attracts thousands of attendees to eat delicious food and hear great music. One of the largest gatherings of Cajun musicians in the world. Hear Cajun, Zydeco, and Swamp Pop tunes while feasting on the freshest crawfish you’ll ever taste. Dance contests, cooking demonstrations, arts & crafts vendors, and a parade. |
|Festival Number of Days	|3|
|Production Company Name	|Lagniappe Productions  |
|Production Company Address	|365 Canal Street, New Orleans, LA 70130 |
|Production Company Phone Number	|504-222-1212|
|Production Company Website	|https://www.lagniappeproductions.com|
|Event 1 Name	|Four Horses| 
|Event 1 Date	|5/5/2023| 
|Event 1 Time	|5:30 PM |
|Event 1 Location	|Crawfish Stage |
|Event 2 Name	|Crawfish Etouffee' Cookoff|
|Event 2 Date	|5/6/2023 |
|Event 2 Time	|11:30 AM |
|Event 2 Location	|Breaux Bridge Tent |
|Event 3 Name	|Mike Broussard & Nu Edition Zydeco |
|Event 3 Date	|5/7/2023 |
|Event 3 Time	|12:15 PM|
|Event 3 Location	|Festival Stage|
|Food Vendor 1	|Buck and Johnny’s |
|Food Vendor 1 Specialties	|Crawfish Etouffee, Crawfish Bisque, Boiled Crawfish |
|Food Vendor 2	|Bayou Teche Seafood |
|Food Vendor 2 Specialties	|Alligator Stew, Shrimp Gumbo , Crawfish Po'boy |
|Food Vendor 3	|Seafood on the Bayou and Boudin Shop |
|Food Vendor 3 Specialties	|Boiled Crawfish, Shrimp Gumbo, Crawfish Jambalaya |

### Score: 90/100
### Feedback: 
1NF, 2NF, and 3NF: All of your relationship arrows are pointing in the incorrect direction and should be flipped. The relationship arrow should start at the primary key in the original table and point towards the foreign key in a separate table. For example, in your 3NF for company id, it should begin at the company id in the production companies table and point towards the company id foreign key in the festivals table. (-10, all relationship arrows are pointed in the opposite direction)
