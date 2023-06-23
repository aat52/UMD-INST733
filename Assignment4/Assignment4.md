GENERAL INSTRUCTIONS:

- Read the full set of instructions and make sure that you understand them all before starting working on the assignment question. You may lose points if you do not follow all of these instructions.

- Submit your assignment as a whole by the deadline stated on Canvas. Do not make partial submissions, (i.e., a subset or portion of the answers).

- Contact the instructors immediately if you think there is an error in any of the questions, or if you feel more clarification is needed.

- The instructors are the best source for help while working on this assignment. Feel free to seek the instructors’ help at any time, as needed.

 

**INSTRUCTIONS:**

Draw an ERD model for the case / situation given below based on available information, using MySQL Workbench. Save the diagram as an .mwb (MySQL Workbench) file. Submit the MySQL Workbench model file through the link available on Canvas. Name your file: yourlastname_a4_cruise.mwb

You may need to make assumptions whenever specific information is not given about some detail that is relevant to your E-R model. Please indicate all such assumptions in a document, and submit it with the MySQL Workbench model file. Name that file: yourlastname_a4_notes.docx (or .pdf, etc.).

Feel free to contact the instructors if you have any questions.

 

**Keep in mind the following points as you work on the ERD model:**

- Attributes of relations must be atomic.

- Avoid unnecessary entities. If you can represent a construct using only one entity, you should not use two or more entities to represent that construct. However, do not leave out any necessary entities, either.

- Avoid one-to-one relationships, unless there are compelling reasons to include one or more of those.

- MySQL Workbench will not allow you to add many-to-many relationships. It will automatically resolve a many-to-many relationship into two one-to-many relationships by inserting an associative entity between the two parent entities.

- Some of the pieces of information given in the narrative may not bear any consequence for the E-R model. (I.e., they may not be relevant to how the ERD model should be drawn.) You should filter out such information as you work on the ERD model.

- Some of the information you need to determine the upper or lower bound cardinalities may not be given in the narrative. In such cases, you will need to make assumptions. While you have some degree of freedom in making your assumptions, try to keep them as realistic as possible, and list them in the notes document.

 

**HAPPY CRUISE LINES**

Happy Cruise Lines has several ships and a variety of cruise itineraries, each involving several ports of call. The company wants to maintain information on the sailors who currently work on each of its ships. The company is not interested in keeping a history of which sailor was assigned to which ship in the past, but only to keep track of the one ship each sailor is assigned currently. It also wants to keep track of both its past and future cruises and of the passengers who sailed on the former and are booked on the latter.

Each ship has at least one and, of course, normally many sailors on it. The unique identifier of each ship is its ship number. Other ship attributes include ship name, weight, year built, and passenger capacity. Each sailor must be assigned to a ship, and to only one ship. Each sailor has a unique sailor identification number, as well as a name, date of birth, and nationality. Some of the sailors are in supervisory positions, supervising several other sailors. Each sailor reports to just one supervisor. A cruise is identified by a unique cruise serial number. Other cruise descriptors include a sailing date, a return date, and a departure port (which is also the cruise’s ending point). Clearly, a cruise involves exactly one ship; over time a ship sails on many cruises, but there is a requirement to be able to list a new ship that has not yet sailed on any cruises at all. Each cruise stops at at least one and usually several ports of call, each of which is normally host to many cruises, over time. In addition, the company wants to maintain information about ports that it has not yet used in its cruises but may use in the future. A port is identified by its name and the country it is in. Other information about a port includes its population, whether a passport is required for passengers to disembark there, and its current docking fee, which is assumed to be the same for all ships. Passenger information includes a unique passenger number, name, home address, nationality, and date of birth. A cruise typically has many passengers on it (certainly at least one). Hoping for return business, the company assumes that each passenger may have sailed on several of its cruises (and/or may be booked for a future cruise). For a person to be of interest to the company, he or she must have sailed on or be booked on at least one of the company’s cruises. The company wants to keep track of how much money each passenger paid (or will pay) for each of their cruises, as well as their satisfaction rating of the cruise, if it has been completed.


### Score: 97/100
