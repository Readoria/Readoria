# Readoria™

**Interactive Storytelling & Reading Comprehension**

*A Java-based EdTech project exploring how interactive narratives can support reading engagement and comprehension.*

**Project status:** In active development  
**Current platform:** Java console application  
**Target audience:** Students aged approximately 11–15  
**Source code:** Private repository

---

## 📖 About Readoria

Readoria is an educational software project that combines interactive storytelling with reading comprehension.

Readers explore branching narratives in which their choices determine how a story unfolds. The broader goal is to connect these reading experiences with activities that encourage readers to reflect on and demonstrate their understanding of the text.

The project grew out of my experience as a qualified teacher and my current studies in Java development.

I'm interested in how software can bring together **engaging reading experiences, meaningful educational content, and accessible design**.

Readoria is both a Java development project and an opportunity to explore how pedagogical ideas can be translated into functioning software.

## 💡 The Concept

Readoria is built around two connected ideas.

**1. Interactive storytelling**

Readers navigate a story by making choices. Different decisions lead to different sections, paths, and endings.

The branching structure gives readers an active role in the experience while providing opportunities to explore how narratives develop.

**2. Reading comprehension**

The educational goal extends beyond making choices.

Readoria is intended to incorporate questions and feedback that help readers engage with what they have read.

The reading comprehension component is currently being developed and evaluated separately. It is not yet integrated into the Java application.

## 💻 Current Java Prototype

The current version is a console-based Java application.

### Implemented functionality

- Interactive stories with branching paths
- Reader choices that determine the next story section
- Multiple possible story endings
- Menu-based navigation
- Input validation
- Console output designed for readability
- File-based storage of basic session information
- Viewing the most recently saved player information

The current prototype includes the stories **Spår Noll** and **Observatoriet**.

### Technical structure

The project uses object-oriented programming to represent stories, their sections, and the relationships between them.

Some of the central components include:

- **`Main`** — handles the application entry point and main menu
- **`Story`** — coordinates story progression
- **`StorySection`** — represents individual sections, their content, and available choices
- **`StoryLibrary`** — provides access to the available stories
- **`StoryData`** — supports the handling of stored session information

The application also uses Java file I/O to save information such as the player's name, age, selected story, last reached section, and session timestamp.

This is currently basic session logging, not a complete progress-saving or reading assessment system.

The architecture continues to evolve as I learn more about Java, software design, and separation of responsibilities.

## 🧠 Educational Development

A major part of Readoria involves exploring how interactive fiction can be connected to reading comprehension.

I'm working on questions such as:

- How can interactive stories support reading engagement?
- How can comprehension questions relate to what a reader has actually encountered?
- How can feedback support understanding rather than simply indicate right or wrong answers?
- How can an application distinguish between narrative choices and evidence of reading comprehension?
- How can the reading experience remain accessible to different learners?

This work includes developing and reviewing story content, question sets, branching structures, and assessment prototypes.

These materials are part of the project's development process and should not be confused with features already implemented in the application.

## 🛠️ Technologies & Development Focus

**Current technology**

- Java
- Object-oriented programming
- File I/O
- IntelliJ IDEA
- Git & GitHub

**Development focus**

- Class design and object relationships
- Branching narrative logic
- Data handling and persistence
- Separation of responsibilities
- Code readability and maintainability
- Input validation and error handling
- Accessible console presentation

## 🚧 Development Status

| Area | Status |
|---|---|
| Java console application | Implemented |
| Branching story navigation | Implemented |
| Multiple stories | Implemented |
| Basic session information storage | Implemented |
| Reading comprehension question prototypes | Developed separately |
| Questions integrated into the application | Planned |
| Answer evaluation and feedback | Planned |
| Reading comprehension results | Planned |
| Further architectural improvements | Ongoing |

### Next Development Goals

The next major development goal is to connect the existing storytelling application with a basic reading comprehension component.

The intended functionality includes:

1. Presenting comprehension questions connected to a story.
2. Recording the reader's first submitted answer.
3. Providing brief explanatory feedback.
4. Keeping comprehension answers separate from the choices that determine the story's path.
5. Presenting a structured summary of reading comprehension results.

These features are part of the planned development and have not yet been implemented in the console application.

## 🎓 Why I'm Building Readoria

My background is in education, where I worked with language learning, reading, and helping students understand complex material.

Now, as a Java development student, I'm interested in exploring these challenges from a software development perspective.

Readoria gives me the opportunity to combine two areas:

**Education:** Understanding learning objectives, reading comprehension, accessibility, and the needs of learners.

**Software development:** Designing application logic, working with objects and data, solving technical problems, and gradually improving code quality.

The project is also a way for me to learn how to turn a larger idea into smaller, manageable development steps.

## 🔒 About This Repository

This repository is a **public showcase of a privately developed project**.

Its purpose is to document Readoria's concept, technical development, educational direction, and progress.

The full application source code is not publicly available at this stage.

This repository is not currently intended as a downloadable or runnable release.

---

### Readoria™

*An ongoing exploration of interactive storytelling, reading comprehension, and educational software development.*

© 2026 Karmatante. All rights reserved.
