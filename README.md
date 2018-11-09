# Linkedin-Learning-Courses-Downloader
Linkedin Learning Courses Downloader is a simple python scraper tool that downloads video lessons from Linkedin Learning
# # How to use
First install the requirements:

pip install -r requirements.txt
In the # config.py file, write your login info and fill the COURSES array with the slug of the the courses you want to download, 
# Example

USERNAME = 'user@email.com'
PASSWORD = 'password'

COURSES = [
    'https://www.linkedin.com/learning/learning-java-3',
  
]
Then excecute the script:
python llcd.py
The courses files will be saved in the out folder.
