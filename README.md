# CS230
SNHU CS230 Projects and Files

Post-Project Q&A

Q: Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?  
A: For this project, my "client" was The Gaming Room, a company with a mobile game called "Draw It or Lose It", which was initially designed for Android. They requested a redesign of the application to become a web-based solution that supports cross-platform play across multiple operating platforms. The software needed to allow various teams and players to participate in game instances, while also ensuring a level of uniqueness across those instances. A major requirement for this project was the use of the Singleton and Iterator patterns to efficiently manage object creation and name validation.

Q: What did you do particularly well in developing this documentation?  
A: With room for improvement, I believe I did well in identifying the architectural and cross-platform deployment concerns relatively early in the project. This integration of design patterns was also neatly implemented in the design document, specifically for the Singleton pattern for the GameService class, and the use of inheritance in the domain model to promote reusability and modularity.

Q: What about the process of working through a design document did you find helpful when developing the code?  
A: Working through the software design document made the code development phase much easier. It forced me to think critically about the structure, how each component would interact, and where performance bottlenecks or conflicts might arise. Having a visual and structured domain model kept my implementation focused and modular.

Q: If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?  
A: If I were to revise one part of the document, I would spend more time fleshing out the System Architecture View section with diagrams and specific technology stacks. While the rest of the document gives a solid logical flow, a concrete depiction of client-server interactions and physical architecture would be helpful for future reference and for any developers who might continue this project.

Q: How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?  
A: To interpret the user’s needs, I focused on how players would interact with the game and what would enhance or hinder that experience. I incorporated responsive design considerations, efficient memory use, and secure, real-time communication with WebSockets. Designing with the user in mind ensures a better user experience and avoids unnecessary rework later. It’s crucial to consider user expectations because the quality of interaction often defines the perceived value of software.

Q: How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?  
A: My approach to software design involved using UML to outline the domain, implementing known design patterns, and evaluating platform compatibility before coding. In future projects, I will continue to use design documents as a blueprint before development. Still, I will also incorporate architectural diagrams, performance benchmarks, and automated testing strategies to further enhance maintainability and scalability.
