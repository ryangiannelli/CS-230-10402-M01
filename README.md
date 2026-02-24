# CS-230-10402-M01
Operating Platforms

The Gaming Room Client Summary

The Gaming Room was the client for this project. They wanted to expand their Android game, Draw It or Lose It, into a web-based application that could run on multiple platforms. The game is similar to Win, Lose or Draw, where teams compete to guess what is being drawn from a library of stock images. Their requirements included supporting multiple teams and players per game, ensuring all game and team names are unique, and making sure only one instance of the game exists in memory at any time.

What I Did Well:
I think I did well in organizing the documentation clearly and explaining the technical recommendations in a way that both the client and development team could understand. The evaluation table comparing different operating platforms was thorough and considered cost, development time, and technical requirements for each option.

Helpful Aspects of the Design Document Process:
Working through the design document before writing code helped me think through the architecture and requirements more carefully. Understanding the constraints like the singleton pattern requirement and unique naming helped guide the code structure. Having the UML diagram planned out made implementing the classes much easier since I already knew how they would relate to each other.

What I Would Revise:
If I could revise one part, I would expand the Domain Model section to include more detail about how the iterator pattern works and why it was chosen over other approaches for checking duplicate names. I could also add more diagrams to visually explain the system architecture.

Interpreting User Needs:
I interpreted the user's needs by carefully reading the requirements and asking what problems the software needed to solve. For example, the requirement for unique names led to implementing the iterator pattern to check existing names before creating new ones. Considering user needs is important because the software is ultimately built for them. If it doesn't meet their needs or is difficult to use, it won't matter how well it's coded.

Software Design Approach
I approached the design by first understanding the requirements, then identifying design patterns that could address those requirements (singleton for single instance, iterator for name checking). I also evaluated different platforms to recommend the best option for the client's needs. In the future, I would continue using design patterns to solve common problems, create UML diagrams to plan class structures, and thoroughly evaluate platform options before making recommendations.
