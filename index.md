# Jobbot

## DESCRIPTION:

Jobbot is an application which makes applying for jobs easier. You only have to enter your Linkedin credentials, and Jobbot does the rest!

Jobbot will essentially scan through your Linkedin profile, curate a high quality, professional resume just for you which gets auto downloaded into your system. Equipped with your Linkedin profile summary and your resume created, Jobbot applies to various well known job application websites by auto filling your details and uploading your resume, thereby saving you a lot of time. You are also given a choice to upload your own resume too. 

Jobbot is a cutting edge app for a busy student/professional who does not need to  spend time seperately to create one's resume or apply for jobs due to its core functionality of creating a resume out of enriched Linkedin profile in real time. The feature of posting on to job portals further enhances its utility thereby letting job aspirants focus on subtler aspects of interview.

Thus if you want to save time and apply for jobs smarter, then Jobbot is THE application for you!

## Track
Task Automation

## Authors
Team Name - Room_Num_219
- [Anshul Jindal](https://github.com/anshul-iiitb16)
- [Mayank Chadha](https://github.com/mayankchadha16)
- [Shreeya Venneti](https://github.com/ShreeyaVenneti)
- [Shridhar Sharma](https://github.com/Shridhar2602)

## DETAILS:

1. Web Automation and Web Scraping are the key ideas for this project. Data from LinkedIn is scraped and used for resume building. Further, some job search sites are automated for filling of candidate's deatils along with uploading the resume.

	List of job search sites automated:
	- [Lenoxex](https://lenoxexsearch.com/submit-resume/)
	- [Newagesys](https://www.newagesys.com/submit_resume.php)

2.  Python programming language along with some of it's major libraries have been used in this project. We also used Figma to design the GUI.

3. Libraries used:
	- Matplotlib - For building the resume from the LinkedIn data, and saving it as PDF
	- Tkinter and Canvas - To build Jobbot's GUI
	- Selenium - To automate login to LinkedIn, button clicks and filling of fields in Job application websites
	- BeautifulSoup - For web scraping the user's Linkedin profile information.
 
4. Following fields are scraped from LinkedIn:
	- Name
	- Profile_URL
	- Roles
	- Location
	- Phone Number
	- Address
	- Email
	- Experiences
	- Education
	- Projects
	- Skills				

## SCOPE:

- Can be used by students/job seekers to build a professional resume and apply for jobs.
<!-- - The application just needs Python to run -->
<!-- 
- We also plan to extend this application to be made available to Android and iOS devices in the future. -->
- Some recuitment websites require Sign Up before filling recruitment forms. We can extend our application by automating such websites.
- Our Application can serve as a handy tool to create professional Resumes from a user's LinkedIn Profile.
- We can import our Application to various Python Frameworks like Django and Flask.

## Installation

Install Selenium library in Ubuntu

```bash
  $ sudo apt-get install python-pip
  $ sudo pip3 install selenium
```

Install lxml library in Ubuntu

```bash
  $ sudo apt-get install python3-lxml
```

Install bs4 library in Ubuntu
```bash
  $ sudo apt-get install python3-bs4
```

Install matplotlib library in Ubuntu
```bash
  $ sudo apt-get install python3-matplotlib.
```

Install Tkinter library in Ubuntu
```bash
  $ sudo apt-get install python-tk
```

## Instructions to run the code:

- Make sure ChromeDriver and all py files are in the same directory.
- By default, we are using Firefox WebDriver for Selenium. Make sure to install the latest version of Firefox before running the script.
- Run Runner.py and the Jobbot GUI will pop up.
- If you want Jobbot to make you a resume:
		- Click on option "Create one"
		- Fill in your LinkedIn credentials - both Username and Password
		- Click on Create button
		- Jobbot will create a new resume in it's working directory and automate the task of filling the forms
- If you prefer to use your own resume:
		- Fill in your LinkedIn credentials - both Username and Password
		- Click on "browse" button and upload your resume
		- Click Submit button
		- Jobbot will automate the task of filling the forms

## Demo

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)