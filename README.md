# Draw It Or Lose It Software Design Document

## *Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?*
This document serves to answer questions and provide recommendations 
for a web based game called, Draw It or Lose It. The game is a guessing game where teams compete to guess the name of the image being drawn to their screen. The game is based on a 1980s television show and the staff at The Gaming Room requested assistance with setting up the environment for the game. The game was required to be designed around a web based system. 

## *What did you do particularly well in developing this documentation?*
During this documentation I feel like I thoroughly articulated the constraints and strengths of each operating system. I spent a fair amount of time ensuring that I was providing accurate information for each operating system. For example, in my initial research it was not clear that a server operating system for Apple is no longer available. 

## *What about the process of working through a design document did you find helpful when developing the code?*
A large benefit of a design document like this is it helps you to understand more of what you're developing. When it comes Linux there are different challenges than you would face trying to develop on Windows. As well during the process of creating this document different applications could be defined that are tailored to the application you're creating. Design patterns can also be identified during the creation of one of these documents. For example this customer desired for only one instance of the game to run in memory, this identifies a singleton pattern. 

## *If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?*
Based on the document I think I would attempt to add more information in places that need it. Certain areas lack extensive details, such as the Client side boxes for each of the operating systems. They feel empty. I also could have used some additional information for the Operating systems architecture in the recommendations field. In this area I mentioned amd64, but it could have been elaborated. 

## *How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?*
The core requirements were centered around creating a team based game with specific constraints, such as a unique team and game names and timed rounds. The singleton pattern and name checks were implemented into the programming to meet these needs. A user's needs being met will directly impact the usability of the application. If a user can not comfortably use a piece of software they will not. Also implementing the requests of the customer ensures the application meets their requirements and satisfies the goals of the customers business. 

## *How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?*
The software design uses object-oriented principles like inheritance to reduce code duplication and plans for scalability with Kubernetes and open-source tools like Linux and Redis for cost-effective, high-performance solutions. Evaluating these choices shows a strong focus on scalability and adaptability to varying loads. Future designs will prioritize user feedback through prototyping, employ advanced design patterns for modularity, and leverage cloud-native solutions to ensure seamless scaling and optimal performance.