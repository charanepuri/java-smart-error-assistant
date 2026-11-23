# Smart Error Assistant
 
## Project Description
A terminal-based helper for looking up common programming errors. Users enter an error message or keyword, and the program searches a locally maintained knowledge base to find related explanations, possible causes, and troubleshooting steps.
 
## Technology Stack
Java (JDK), OOP, Scanner, String handling, ArrayList/HashMap, collections, optional file handling, and exception handling.
 
## Features
- Accept an error message or keyword from the user.
- Normalize and search entered text against known error patterns.
- Display matching error descriptions and possible causes.
- Provide suggested troubleshooting steps for known issues.
- Organize knowledge-base entries by technology or category.
- Optionally add or update knowledge-base records.
- Show a clear no-match message when no relevant entry is found.
 
## Database Design
No database is required for the basic version. The knowledge base can be represented with Java collections or stored in a local text/CSV/JSON file. If a database is introduced, an ErrorEntry table could contain error_id, technology, error_pattern, description, possible_cause, and suggested_solution.
 
## Learning Outcomes
- Practice String processing, normalization, and keyword matching.
- Represent error records using Java classes.
- Use collections to store and search a knowledge base.
- Separate search logic, data, and console presentation.
- Understand the limitations of rule-based matching compared with AI-powered diagnosis.
 
## Explanation
The user enters an error message or a distinctive keyword. The application normalizes the input and searches its stored error entries using exact or partial matching rules. It then displays the most relevant known entry, including its description, likely cause, and recommended steps. Results depend on the quality and coverage of the knowledge base.
 
## Conclusion
Smart Error Assistant demonstrates how structured data and search logic can support a useful developer utility. It is a rule-based troubleshooting project and should not be represented as an AI model unless genuine AI integration is implemented.
 
## Author
**Charan Teja EPURI**  
*Aspiring Full Stack Developer*
 
- [Django Portfolio](https://portfolio-site-django.onrender.com)
- [GitHub](https://github.com/charanepuri)
- [React Portfolio](https://charan-react-portfolio.vercel.app)
- [LinkedIn](https://www.linkedin.com/in/charan-teja-972aa9231)
- [Flask Portfolio](https://flask-developer-dashboard-portfolio.onrender.com/)

 
