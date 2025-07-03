Project Description
The Passion to Profession Finder is a web application designed to help parents guide their teens in discovering potential career paths based on their interests. This interactive tool combines AI-powered career suggestions with practical project ideas to help teens explore fields that align with their passions.

Key Features:
Interest-based career matching: Input your teen's interests (e.g., art, coding, helping people) to receive tailored career suggestions

Detailed career profiles: Each suggested career includes matching interests, required skills, and starter projects

AI-powered recommendations: Uses Google's Gemini AI to analyze interests and suggest relevant career paths

Data storage: Saves submissions to Google Sheets via Google Apps Script

Responsive design: Works on all device sizes with smooth animations and transitions

User-friendly interface: Clean, intuitive design with helpful visual cues

Screenshots
![image](https://github.com/user-attachments/assets/6ee2ff1e-1aeb-4186-8e32-ca1f6aa5462c)


Technologies Used
Frontend: HTML5, CSS3, JavaScript

Styling: Tailwind CSS with custom animations

AI Integration: Google Gemini API

Backend Integration: Google Apps Script (for data storage)

Hosting: Can be deployed on any static hosting service (GitHub Pages, Netlify, Vercel, etc.)

Setup Instructions
Prerequisites
Google account (for Apps Script deployment)

Google Gemini API key (free tier available)

Installation
Clone this repository:

bash
git clone https://github.com/yourusername/passion-to-profession-finder.git
Open frontend.html in your code editor

Configuration
Google Apps Script Setup:

Create a new Google Apps Script project

Copy the code from backend.gs (to be created) into the script editor

Deploy as a web app https://github.com/ayushshinde19/Passion-to-Profession-Finder/blob/main/Passion-to-Profession%20Finder%20Web%20App%20with%20Google%20Sheet%20Integration.pdf

Replace the placeholder URL in frontend.html with your deployed web app URL

Gemini API Key:

Get an API key from Google AI Studio

Replace the placeholder API key in frontend.html

Usage
Open frontend.html in a web browser

Fill in your name and email

Enter your teen's interests (comma-separated or one per line)

Click "Find Professions" to get AI-generated career suggestions

Explore the recommended careers and starter projects

File Structure
text
passion-to-profession-finder/
├── frontend.html          # Main application interface
├── README.md              # This documentation file
└── backend.gs             # Google Apps Script for data handling (to be created)
Customization
You can easily customize:

Color scheme by modifying the Tailwind CSS classes

Career data by editing the careerData array in the JavaScript

Animations by adjusting the CSS @keyframes rules

Form fields to collect additional information

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.

License
This project is open source and available under the MIT License.

Support
For questions or support, please open an issue in this repository.
