**Case Study: Story-Driven Choice-Based Game (Episode Inspired)**

**Gameplay**

This project is a story-driven, choice-based game inspired by Episode – Choose Your Story. The core gameplay revolves around interactive dialogue, where players are repeatedly presented with narrative choices that influence the direction of the story. At each decision point, the player selects between two options, and the narrative branches accordingly, forming a binary decision tree that unfolds over time.
Rather than immediately revealing outcomes, the game emphasizes delayed consequences. Players must progress through the story to understand how their earlier decisions shape character relationships, narrative tone, and eventual endings. This structure encourages replayability and reflection, as different choice paths lead to distinct story outcomes.
The game also features character expression and customization systems. Characters dynamically change facial expressions to match dialogue context, enhancing emotional engagement. In addition, players can customize characters by modifying skin tone, clothing, hairstyles, and shoes. These systems are integrated seamlessly into the narrative flow, ensuring that personalization does not disrupt storytelling but instead reinforces player immersion and identification with characters.

**Problems Encountered**

One of the primary challenges in developing this game was designing a scalable narrative system that could support branching stories without becoming rigid or developer-dependent. Hardcoding dialogue flows quickly proved impractical, especially as story complexity increased.
To solve this, I designed a fully data-driven narrative system using Scriptable Objects. Each dialogue node, choice, and transition was abstracted into reusable data assets rather than fixed code. This approach allowed the story structure to function as a modular graph, where narrative logic and content were cleanly separated from gameplay systems.
A critical design challenge was usability: the system needed to be accessible not only to developers but also to non-technical content creators. The final implementation allows anyone with story content—such as writers or designers—to create and modify complete storylines directly within the editor, without writing a single line of code. Ensuring clarity, validation, and error prevention within this workflow required careful structuring of data relationships and constraints.
Another challenge involved synchronizing narrative progression with character expressions and customization. Dialogue state, emotional context, and visual presentation had to remain consistent across branching paths, which required robust state management and clean separation of narrative, visual, and customization systems.

**Learning**

By implementing a narrative system based on Scriptable Objects, I gained practical experience in designing extensible, maintainable, and scalable architectures for interactive content. The separation of data and logic reflects principles of software engineering emphasized in applied computer science, including modularity, abstraction, and reusability.
The branching dialogue structure functioned as a runtime decision graph, strengthening my understanding of state machines, graph-based data representations, and event-driven systems—concepts that are central to game engines, simulations, and interactive media technologies.
Equally important was the focus on tool usability and interdisciplinary workflows. Designing a system that empowers non-technical contributors reflects real-world game production environments and aligns with H-BRS’s emphasis on collaborative development across technical and creative disciplines.
Overall, this project demonstrates my ability to translate narrative design requirements into robust technical systems, balancing player experience with engineering rigor. It reflects my readiness for graduate-level study in Game Technologies by showcasing applied system design, interactive storytelling, and the development of flexible tools for content-driven games.
