# Study Portal Readme

This Study Portal is a web application built with Django, designed to help students manage their study tasks effectively. It provides features such as a todo list, homework management, YouTube integration, note-taking, conversion tools, and access to Wikipedia.

<h2>Home Page</h2>
<img width="919" alt="HomePage" src="https://github.com/hamda288/StudentStudyPortal/assets/96077150/8258e8ad-873f-4000-9a6a-d604748ff424">

<h2>Profile</h2>
<img width="918" alt="profile" src="https://github.com/hamda288/StudentStudyPortal/assets/96077150/58b25b5a-6778-42ed-9913-60c58b531b8b">

<h2>Notes</h2>
<img width="917" alt="Notes" src="https://github.com/hamda288/StudentStudyPortal/assets/96077150/61151420-b96d-4986-a960-1eb064c37d60">

<h2>Homework</h2>

<img width="915" alt="Homework" src="https://github.com/hamda288/StudentStudyPortal/assets/96077150/f196f9a0-82e5-4dcc-b266-d8be01419085">

<h2>Todo</h2>
<img width="919" alt="Todo" src="https://github.com/hamda288/StudentStudyPortal/assets/96077150/7fe3362b-5507-4cd0-99b9-6d580d429089">

<h2>Youtube</h2>
<img width="919" alt="youtube" src="https://github.com/hamda288/StudentStudyPortal/assets/96077150/cae5eca5-8206-4f51-9de2-dc0366db8222">

<h2>Books</h2>
<img width="916" alt="book1" src="https://github.com/hamda288/StudentStudyPortal/assets/96077150/054f0fc0-e1e8-4f9e-93c5-f2ab2870b92c">

<h2>Wiki</h2>
<img width="916" alt="wiki" src="https://github.com/hamda288/StudentStudyPortal/assets/96077150/c2c5664d-c30b-4b25-89cf-2e70759278c3">

<h2>Conversion</h2>
<img width="918" alt="Conversion" src="https://github.com/hamda288/StudentStudyPortal/assets/96077150/37e8a504-d06e-4b48-8b88-0fe3dbee7ad9">


## Getting Started

To run the Study Portal locally, follow these steps:

1. Clone the repository from GitHub:
   ```
   git clone https://github.com/your-username/study-portal.git
   ```
2. Navigate to the project directory:
   ```
   cd study-portal
   ```
3. Create and activate a virtual environment (optional, but recommended):
   ```
   python3 -m venv venv
   source venv/bin/activate
   ```
   ```
4. Set up the database:
   ```
   python manage.py migrate
   ```
5. Create a superuser (admin) account:
   ```
   python manage.py createsuperuser
   ```
   Follow the prompts to set a username and password.
6. Start the development server:
   ```
   python manage.py runserver
   ```
7. Access the Study Portal in your web browser at `http://localhost:8000`.

## Features

### Todo List
- Students can create a todo list to keep track of tasks they need to complete.
- They can add and delete tasks.
- Completed tasks can be marked as done.

### Homework Management
- Students can manage their homework assignments.
- They can add new assignments with due dates and descriptions.
- Homework can be marked as completed.

### YouTube Integration
- The Study Portal integrates with YouTube to help students access educational videos.
- Students can search for videos, watch them directly on the website, and add them to their favorites for later reference.

### Note-Taking
- The portal provides a note-taking feature to help students jot down important information.
- They can create and organize notes by topics or subjects.
- Notes can be edited and deleted as needed.

### Conversion Tools
- Students have access to conversion tools for common units of measurement.
- They can convert values between different units, such as length and weight.
- This feature helps students easily convert values for assignments or experiments.

### Wikipedia Access
- The Study Portal offers access to Wikipedia for quick reference and research.
- Students can search for articles on various topics and read the content directly within the portal.

## Contributing

Contributions to the Study Portal are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch from the `main` branch for your changes.
3. Make your desired changes and additions.
4. Test your changes to ensure they work as expected.
5. Commit your changes with descriptive commit messages.
6. Push your branch to your forked repository.
7. Submit a pull request to the original repository, explaining your changes and why they should be merged.


## Acknowledgements

The Study Portal was developed by [Hamda Ahmad] as a personal project. It was built using the Django web framework and incorporates various libraries and APIs to provide its functionality. Special thanks to the Django community, YouTube API, Wikipedia, and the developers behind the conversion libraries used in this project.
