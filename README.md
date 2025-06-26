 CuroAI Goal Submission Prototype
A smooth and at the same time  responsive web application prototype for goal submission and deadline setting, built as part for the  1Direction Global frontend internship technical interview by me shaadaab ilyas 
Project simple overlook:

This prototype allows users to easily be able to 

Enter detailed goal descriptions

Set target deadlines

Submit goals to the CuroAI backend API

Receive confirmation of successful submission

The application i feel perfectly serves as the frontend interface for CuroAI's AI-powered goal planning system


this application can be used for front ends front interface its really a very low version of what all that can be added to make it really more  user friendly 
 a bit why i chooses what i choose-
 Visual Design as u can see uses 
Modern gradient background creates an engaging, professional appearance
Clean white card layout provides focus and readability
Responsive design ensures functionality across all device sizes
Smooth hover animations enhance user experience

User Experienceiis better by 
Form validation prevents empty submissions
Loading states provide feedback during API calls
Success/error messages keep users informed
Date validation prevents past dates from being selected
Accessible form labels improve usability

Technical Implementation:
Single-page application for simplicity and fast loading
Async/await for clean API handling
Error handling for network failures
JSON data structure matching API requirements
View Live Prototype (https://shaadaab-design.github.io/curoai-goal-prototype/)

hows the api intergreated?
The prototype sends POST requests to: https://curoai.free.beeceptor.com/goals
Data Format:
json{
  "goal": "User's goal description",
  "deadline": "YYYY-MM-DD",  
  "timestamp": "ISO timestamp"
}
how would u run this locally-?

Download the index.html file
Open in any modern web browser
No build process or dependencies required at all making it very easy and efficient

what can be added in my opion to better this?

Goal categories and tags
Progress tracking integration
Calendar visualization
User authentication
Goal sharing capabilities

dev
Built by Mohmmed shaadaab ilyas  for the 1Direction Global Frontend Development Internship

