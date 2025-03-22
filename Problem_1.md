# Problem 1: Categorized Training Questions (Separated from Answers)
## Client Need:
Developers want categorized training questions separate from answers for self-affirmation training.
## Validation:
1. How do you currently categorize training questions?

Answer:

Currently, training questions are manually categorized by subject or topic area, depending on the specific needs of the training program. The categories may include things like "Basic Knowledge," "Advanced Concepts," "Technical Skills," or "Soft Skills," depending on the context.

2. What specific categories do you use for training questions?

Answer:

The specific categories may vary based on the training objectives, but common categories include:
-	Technical Knowledge (e.g., programming languages, hardware, etc.)
-	Behavioral Skills (e.g., communication, leadership, teamwork)
-	Compliance & Policies (e.g., legal, safety, ethics)
-	Process & Procedures (e.g., workflows, guidelines)
-	Product Knowledge (e.g., features, use cases, best practices)

3. Do you require the system to suggest categories automatically?

Answer:

Yes, it would be helpful if the system could automatically suggest categories based on the content of the questions. This would save time and help maintain consistency across the categorization process. The system could use machine learning models or predefined rules to analyze the question's content and suggest relevant categories.

4. Should developers be able to create custom categories?

Answer:

Yes, developers should have the ability to create custom categories. This would allow for greater flexibility and ensure that the system can accommodate unique needs or changes in categorization structure over time. Custom categories would be particularly useful for projects with specific requirements or when new types of training content arise.

5. How do you expect the interface for managing categorized questions to look like?

Answer:

The interface should be intuitive and user-friendly. It might include features like:
-	A search bar for quickly finding questions.
-	Dropdowns or checkboxes to select or assign categories to questions.
-	Drag-and-drop functionality for easy re-categorization.
-	A clear list view of questions with their associated categories.
-	Batch editing options to update multiple questions at once.
-	Visual indicators showing the status of each question (e.g., uncategorized, categorized).
---
# Functional Requirements:
1.	The system shall separate questions from answers for self-affirmation training.
2.	The system shall allow developers to categorize training questions manually and automatically.
3.	The system shall enable users to filter, search, and manage categorized questions.
---
Github Issues

Issue #1: As a developer, I want the system to store questions and answers separately so that I can ensure clarity and improve self-affirmation training.

### Purpose:

Following discussions with the client, it was determined that storing questions and answers separately in the system will improve clarity, simplify management, and support better tracking of individual components for self-affirmation training.

Sub-Issues:
1.	Issue #2: Implement separate tables for storing questions and answers.
2.	Issue #3: Develop a method for retrieving answers associated with a specific question.
3.	Issue #4: Design a user interface for managing questions and answers.
4.	Issue #5: Implement an API endpoint to interact with questions and answers.

Issue #2: As a developer, I want an automatic classification feature for questions so that I can save time and improve efficiency.

### Purpose:

Following discussions with the client, an automatic classification system will be implemented to categorize training questions, saving time and ensuring consistency in question categorization.

Sub-Issues:
1.	Issue #6: Choose and implement an automatic classification algorithm.
2.	Issue #7: Integrate the classification system with the question management interface.
3.	Issue #8: Allow manual correction of automatic classifications.
4.	Issue #9: Create a system for training and improving the classification model.

Issue #3: As a developer, I want to manually categorize training questions so that I can ensure proper organization based on project needs.

### Purpose:

Following discussions with the client, it was agreed that manually categorizing questions will allow for better organization and alignment with project goals, improving data accessibility and retrieval.

Sub-Issues:
1.	Issue #10: Create a category management system.
2.	Issue #11: Design a user interface for selecting and managing categories.
3.	Issue #12: Implement a category filter feature.
4.	Issue #13: Develop a database structure to store category information.

Issue #4: As a developer, I want to filter and search training questions by category so that I can quickly locate specific data I need.

### Purpose:

Following discussions with the client, it was agreed that implementing a robust filtering and search functionality will allow users to efficiently locate training questions by category, enhancing productivity and usability within the training data repository.

Sub-Issues:
1.	Issue #14: Design and implement a search bar for keyword-based searching.
2.	Issue #15: Implement a filtering system based on categories.
3.	Issue #16: Integrate search functionality with the database.
4.	Issue #17: Optimize search performance for large datasets.

Issue #5: As a developer, I want to edit, delete, or update categorized training questions so that I can keep the training data up to date.

### Purpose:

Following discussions with the client, the ability to edit, delete, or update categorized training questions will ensure that the system remains current and allows for flexibility in managing the training data repository.

Sub-Issues:
1.	Issue #18: Implement UI components for editing and deleting questions.
2.	Issue #19: Implement backend logic for updating and deleting questions.
3.	Issue #20: Develop an undo or confirmation mechanism for deleting questions.
4.	Issue #21: Update the search and filter system to reflect any changes made to questions.
