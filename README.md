# "Planning Poker" for NAO robot [v.1.0]
*Right now this project is only available in english!*<br>

### About

Planning poker is a collaborative, team-based method of estimation used by agile teams. This method is used in agile software development 
and project management to help teams working together on a project to determine the effort required to complete specific tasks. The team 
comes together to estimate the effort required to complete a set of specific tasks by selecting a card from a deck of planning poker 
cards, which typically feature numbers representing different levels of effort, using the Fibonacci scale. 

### How the program works

The application "Planning Poker with NAO" has five main parts, i. e. “Introduction”, “Explanation”, “Planning Poker”, “Create protocol” 
and “Ending”. In the “Introduction”, the guidelines are presented, on how the participants can interact with the robot, for example by
speech or by pressing the foot bumpers. In the section “Explanation”, the robot explains the concept of planning poker, its rules and
tasks to be estimated. Next part “Planning Poker” is the actual play of the game with estimation of each tasks by the team of players. 
<br>
In the “Create protocol” part, the NAO robot creates a document with the results from each estimation. The estimated numbers are automatically 
saved and matched with the corresponding items in a PDF file. After every estimation round, the agreed number from the Fibonacci scale is 
appended to a local text file. At the very end of the simulation, a python script takes every entry and matches the items to the numbers.
The file can be accessed in Choregraphe in the tab Connection > Advanced > File Transfer. The PDF file can be later accessed and downloaded 
from Choregraphe. Finally, the “Ending” part includes the reflection question and the review of learnings.

### What do you need?

You  need your NAO robot and a deck of planning poker cards.

### Plans of further development:

We are currently developing a German version for teachers.

### Choregraphe screenshot:

![WhatsApp Image 2023-02-24 at 13 22 27](https://user-images.githubusercontent.com/68842909/221185247-b4dcadd9-987c-4841-a40f-12494261698a.jpeg)


---

### Changelog
