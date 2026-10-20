# Tech Stack Evaluation

## Project
Web-based Lost and Found System

## Requirements that drive the decision

- FR1: The system shall allow users to register and log in.
- FR2: The system shall allow users to create a post for a found item with its image and location found.
- NFR1: The system shall load item listings within 3 seconds under normal usage conditions.
- NFR3: The system shall allow users to submit a found item post in less than 5 minutes.

## Options

- **Option A:** Static website (HTML, CSS, JavaScript) on GitHub Pages
- **Option B:** Flask web application with SQLite database
- **Option C:** PHP web application with MySQL databas

## Decision matrix
Weight: how important the criterion is for YOUR project (1 = low, 5 = high).
Score: how well each option does (1 = poor, 5 = excellent).
Weighted score = weight x score. Add them up for each option.

| Criterion                          | Weight | A score | B score | C score |
|------------------------------------|--------|---------|---------|---------|
| Fits my requirements               |   5    |    2    |    5    |    4    |
| Skills I already have              |   4    |    4    |    5    |    3    |
| Time to build before my deadline   |   5    |    5    |    4    |    3    |
| Free hosting and tools             |   4    |    5    |    4    |    5    |
| Performance and security needs     |   4    |    2    |    4    |    4    |
| Room to grow later                 |   3    |    1    |    5    |    4    |
| **Total (weighted)**               |        |    82   |   112   |    95   |


## Decision Record
- **Context:** The project needs user authentication, item posting, and image uploads. It must be completed within a limited time and budget.
- **Decision:** Option B, Flask web application with SQLite database.
- **Reasons:**
  - Supports all project requirements.
  - Easy to develop with existing skills.
  - Provides better scalability than a static website.
- **Consequences:**
  - Easier to manage data and user accounts.
  - Requires deployment and database configuration.
- **Risks and next review:**
  - Deployment or database issues may occur.
  - Review the chosen stack after completing the core features.
