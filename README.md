<h1 align="center">
  <br>
<img
src="https://raw.githubusercontent.com/parth-03083/htl-hirest/main/static/assets/img/Hirest.png" alt="Hirest" width="200">
  <br>
  Hirest
  <br>
</h1>

# 🧐 Project philosophy

> Hirest is an all-in-one hiring platform which includes job posting, job application, job application tracking system and recieving it's update on phone as text messages using Twilio. Also, we have implemented the unique feauture of broadcasting service for reducing the tediousness of sharing same documents to multiple users. This feature reads a list of recipients from a CSV file and then broadcasts it to them. 
> 
> There are other features like Skill Development Suggestion, Skill-Based Job Suggestions, Resume builder, and rigorous filtering system to help you find exactly what you are looking for.
> 
> Also, we have uploaded our code on Github and registered the domain name for our platform as "hirest.co" from GoDaddy Registry. For generating the resume, we have used the ApyHub API to convert the profile into a Resume of the user.

# 👨‍💻 Tech stack

Here's a brief high-level overview of the tech stack the Well app uses:

- This project uses the [django](https://www.djangoproject.com/). django is a python back-end framework which supports MVC architecture.
- For persistent storage (database), the app uses the [SQLite](https://sqlite.org/index.html) package which allows the app to create a custom storage schema and save it to a local database.
- To engage with users and provide them life changing updates, the platform uses the [Twilio](https://www.twilio.com/).

## Key Features

*   **Job/Internship Search:** Job seekers can search for job/internship opportunities based on their skills and qualifications.
*   **Candidate Search:** Recruiters can search for candidates based on their requirements. 
* **Application Process Tracking:** Both job seekers and recruiters can track their application processes and stay updated on the status of their applications.
*  **Single Platform for Application Process:** This platform provides a single platform for the entire application process, from interview scheduling to offer letter generation.
* **Custom Templates:** Custom templates can be used to create documents required for the application process.
*  **Resume Builder:** Job seekers can create their resumes using the platform's built-in resume builder.
* **Blog:** The platform includes a blog section which we are planning to post resourceful content.

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Python](https://www.python.org/)  installed on your computer. From your command line:

````bash
# Clone the repository
$ git clone https://github.com/Jay2219/SignVerse

# Go into the repository
$ cd hirest

# Create a Virtual Environment
$ python -m venv env # for windows 
or 
$ python3 -m venv env # for mac/linux


# Install dependencies
$ pip install -r requirements.txt
or
$ pip3 install -r requirements.txt

# create your database
$ python manage.py makemigrations 
or 
$ python3 manage.py migrate
