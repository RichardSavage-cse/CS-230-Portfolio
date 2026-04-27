# CS-230-Portfolio
Software Design and Draw It or Lose It project for CS-230


# CS 230 Portfolio Reflection – README

## Briefly summarize The Gaming Room client and their software requirements.

The client for this project was The Gaming Room, the company behind the game Draw It or Lose It. Their game was originally created as an Android-only application, and they wanted to expand it so it could run across multiple operating systems such as Windows, macOS, Linux, Android, and iOS. They needed a web-based application using a client-server architecture that would allow multiple users, teams, and game sessions to run at the same time. The system also needed secure authentication, unique game and team names, strong performance, and scalability so the application could support future growth.

## What did you do particularly well in developing this documentation?

I believe I did particularly well in explaining the technical recommendations in a way that connected directly to the client’s needs. I clearly compared Linux, Windows, macOS, and mobile platforms and explained why Linux was the best choice for hosting the application. I also did a strong job explaining memory management, storage management, distributed systems, and security requirements while keeping the document organized and easy to follow.

## What about the process of working through a design document did you find helpful when developing the code?

The design document helped me understand the structure of the application before writing any code. It allowed me to plan how the different classes such as Game, Team, Player, and GameService would work together. The UML diagram was especially helpful because it showed the relationships between the classes and how object-oriented programming principles like inheritance, encapsulation, and abstraction would be used. This made it easier to implement the singleton pattern and iterator pattern correctly in the Java application.

## If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of the document, I would improve the Evaluation section by adding more detailed comparisons between the different operating platforms. I would include more real-world examples of how Linux, Windows, and macOS are used in large-scale hosting environments and provide stronger cost comparisons for long-term maintenance. This would make the final recommendation even stronger and better supported.

## How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I interpreted the user’s needs by focusing on the client’s goal of making the game available on multiple platforms while maintaining strong security and performance. Instead of designing separate applications for each platform, I recommended a web-based client-server architecture that would allow all users to connect through browsers or mobile devices. I also included secure login systems, database management, and scalable server recommendations. Considering the user’s needs is important because the software must solve the client’s actual business problem. If the design does not meet those needs, the software will not be effective or successful.

## How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached designing software by first identifying the business requirements and technical requirements of the client. I then used UML diagrams, platform comparisons, and design patterns to organize the structure before writing code. I focused on scalability, security, and maintainability so the system could continue growing over time. In the future, I would continue using design documents and UML modeling because they help prevent major issues during development. I would also spend more time gathering direct user feedback early in the design process so the final product better matches user expectations and business goals.
