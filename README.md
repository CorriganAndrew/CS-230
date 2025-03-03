# CS-230

Summary of the Client and Their Requirements
The Gaming Room needed a web-based version of its already popular game “Draw It or Lose It”, that supports multiple teams and players in real time while maintaining only one active game instance in memory. The solution had to be scalable, accessible on both web and mobile, and capable of handling high traffic.

Highlights of the Documentation Process
A major strength of the documentation was the clear definition of architecture and design constraints from the start. Specifying a single-instance requirement and using inheritance for teams and players helped focus on core functionality and eliminate redundancy.

Helpful References and Resources
Key resources included UML diagrams for visualizing class relationships, platform-specific documentation to compare hosting options, and design pattern guides for scalability and maintainability. In future projects, integrating these resources earlier would further refine requirements and design.

Interpreting and Implementing User Needs
The design centers on scalability, unique naming, and a single active game instance by leveraging inheritance and a central GameService class. This approach ensures the product remains user-friendly and aligned with the client's gameplay and business objectives.

Approach to Software Design
The design process combined top-down analysis with iterative refinement, focusing on high-level requirements such as single-instance management and platform accessibility. Future projects will continue to use agile iterations, prototyping with UML modeling, and regular stakeholder check-ins to maintain alignment with client goals.
