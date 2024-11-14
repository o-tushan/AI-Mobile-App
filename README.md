In the Fall semester of 2024, I had the pleasure of making a mobile app with AI functionality. 

The app is built in Swift, and you are able to log in and ask the app ethical questions, where the app will then utilize ChatGPT
to give you a response based on your preferences. When you ask your question, you can tell the AI to answer for, neutral, or against,
customizing the ethical stance that the AI takes.

The username and password is hardcoded with the potential for easy database integration in the future. The credentials to log in are as follows:
Username: testuser@test.com (not case sensitive)
Password: Testpassword (case sensitive)

The app has many functional pages that would be utilized with a database, including create/delete account, forgot/change password, and past chat
history. The app also has a randomized question feature, where it will randomly select 1 of 4 ethical questions that you can then choose for, 
neutral, and against for the AI to answer. 

The app is missing a ChatGPT API key, and this is for security reasons and GitHub's warning against uploading keys to repositories. To make the 
app work, all you need to do is go to the 'GetAnswer' page and find the two sections where an API key is needed, marked by comments. Once you 
replace the temp words with a functional API key, the app will function properly.
