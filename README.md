This repository contains the final submission for CS-230: Software Design Journal at Southern New Hampshire University.  
It includes the fully completed Project Software Design Template, covering all three project stages:

- Project One: Executive Summary, Requirements, Design Constraints, and Domain Model.
- Project Two: Evaluation
- Project Three: Platform Recommendation

## Files
- Project 3 Software Design Template.docx

This repository was created as part of the final Module Eight assignment for CS-230.


CS 230 Module Eight Journal

1. Briefly summarize The Gaming Room client and their software requirements.

The Gaming Room is a company that developed the Android-based game Draw It or Lose It and wanted to expand it into a scalable, cross-platform, web-based version. They needed software that would allow players to access the game across Linux, Mac, Windows, and mobile environments through a web application. Their requirements focused on using object-oriented programming (OOP) principles, following a modular design, and ensuring that games, teams, and players would each have unique names. It was important for the design to be scalable and future-ready for possible database and front-end integration.

2. What did you do particularly well in developing this documentation?

One thing I feel I did particularly well was keeping the documentation organized and easy to follow. I used clear section headings and wrote in a way that would be understandable even for someone unfamiliar with the project. I also worked to make sure each part of the documentation tied directly back to the project goals. For example, in the Requirements and Domain Model sections, I carefully connected the functional needs with the design choices, helping the reader understand the reasoning behind the structure.

3. What about the process of working through a design document did you find helpful when developing the code?

Working through the design document was very helpful because it gave me a clear roadmap before writing any code. Having everything planned out — like the class hierarchy and design constraints — made the actual coding much smoother. For instance, when coding the GameService class, I could easily reference the Domain Model and remember to enforce the Singleton pattern. The design document helped me avoid confusion about relationships between classes and prevented me from forgetting important project requirements during development.

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of my documentation, I would focus on expanding the Domain Model section by adding more real-world examples. For instance, I could have explained how the Team class could represent different competitive groups in a real game setting. Adding these examples would help make the model even easier to understand for someone new joining the project later on. It would also better show how the abstract design connects to real-world use cases.

5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I interpreted the user’s needs by closely reading the project description and noting important details like the need for cross-platform compatibility, unique naming, and future scalability. I made sure the design addressed those needs by using universal Java practices, avoiding OS-specific code, and enforcing unique names through iteration checks. It's important to consider the user's needs because if the software doesn't solve their real problems, it won’t be useful no matter how technically sound it is. In this project, making sure users could create and manage games without conflicts was critical to meeting the client’s goals.

6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached designing the software by first carefully reviewing all project requirements and then sketching out the main components on paper before building the Domain Model. I used object-oriented principles like inheritance, abstraction, and encapsulation to keep the design organized. In the future, I would continue using the same careful planning approach but would also try creating more detailed diagrams, like a simple sequence diagram, to better visualize interactions between classes. This would help catch potential issues earlier and make the project easier to expand later.



