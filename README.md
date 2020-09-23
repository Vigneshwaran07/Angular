# POC 1: Game and Guest Registration

Objective: This application should allow admin to create games and the add guests to the game.
Users of the System: Admin
Functional Requirements:
Admin
1. Admin need to login to the application using a login screen
2. Can view the list of games created.
3. List should show Game name, Game Date, Game Venue, Home team and Away team, number of Guests. Sorting
should be game name ascending.
4. List should have a search functionality (single textbox) to search the games by name or team name.
5. List should have filter feature. Filter by Team name (multi-select). Teams can be preloaded in the database table.
6. Can create new game. New Game page should have Name, Venue, Home team and Away team as input.
7. All fields are Mandatory. Validation should be done in front-end
8. Game name validation should be unique. It has to be validated in backend before saving a game.
9. Add Guest button should be available in the list page.
10. When the button is clicked all future games should be populated.
11. When admin click on a game, Add Guest popup should be displayed
12. Guest can be given as input. Multiple guest can be added by clicking the Add more.
13. Guests can be imported using an excel sheet also. List of Guest name should be populated in an excel sheet.
14. Admin can import that sheet into the system. Application should validate the sheet and read the guest list and
save in the database.
15. Admin can have an export guest list feature to see the list of guests for a game. An excel sheet should be
generated with guest names.
16. Admin can have an option to export the games too.
17. Can logout.
Tools to be used:
Use any IDE to develop the project.
Create as a maven web project.
MySQL for the database.
