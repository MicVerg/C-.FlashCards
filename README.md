# FlashCards
A project with focus on back-end with C#, getting to know DTOs, MSSQL and SQL in general.
Since there's a focus on back-end, the display happens in console.

The question is a word or sentence in a foreign language, the answer you are supposed to give is the English translation.
Each card is part of a stack (For example the stack "Arabic").

[Watch this demo](https://www.youtube.com/watch?v=QdhPAbm_QHA)
# Given Requirements
- [x] This is an application where the users will create Stacks of Flashcards.
- [x] You'll need two different tables for stacks and flashcards. The tables should be linked by a foreign key.
- [x] Stacks should have an unique name.
- [x] Every flashcard needs to be part of a stack. If a stack is deleted, the same should happen with the flashcard.
- [x] You should use DTOs to show the flashcards to the user without the Id of the stack it belongs to.
- [x] When showing a stack to the user, the flashcard Ids should always start with 1 without gaps between them. If you have 10 cards and number 5 is deleted, the table should show Ids from 1 to 9.
- [x] After creating the flashcards functionalities, create a "Study Session" area, where the users will study the stacks. All study sessions should be stored, with date and score.
- [x] The study and stack tables should be linked. If a stack is deleted, it's study sessions should be deleted.
- [x] The project should contain a call to the study table so the users can see all their study sessions. This table receives insert calls upon each study session, but there shouldn't be update and delete calls to it.

# Features
- MSSQL database connection
- Use of DTO's
- Linked tables with cascading deletes
  
# Challenges
The main challenge was comprehending the links between tables, and how to put it all together.

# Lessons learned
- DTOs
- SQL linked tables
- Exposure to SQL in general

# Areas to improve
- Comfortability with SQL
