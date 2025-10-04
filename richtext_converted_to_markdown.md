\# StellerAtlas - Your Gateway to the Cosmos 🌌

\## Team Information

\*\*Team Name:\*\* \[STELLAR ATLAS\]

\*\*Team Members:\*\*

\- \[Member 1 - TANISHQ KAUSHAL\] - \[TEAM LEADER / FULL STACK\]

\- \[Member 2 -ANVAY GHARE\] - \[LEAD FRONTEND\]

\- \[Member 3 -AKSHAT UPADHYAY\] - \[FRONTEND / UI UX DESIGNER\]

\- \[Member 4 - RISHIKESH SHARMA \] - \[CONTENT PLANNING AND EXECUTION HEAD\]

\---

\## Project Name

\*\*StellerAtlas\*\*

\---

\## Project Abstract

StellerAtlas is an innovative astronomy education platform designed to democratize celestial knowledge and make stargazing accessible to everyone. The platform addresses the critical gap in astronomy education where existing solutions fail to efficiently guide beginners through the complex world of stargazing, with resources that are fragmented, overly technical, and lacking structured learning paths.

Our solution combines comprehensive educational content covering astronomy basics, constellations, equipment selection, and observation techniques with an automated resource delivery system. Users can access detailed guides on topics ranging from basic sky navigation to advanced astrophotography, all presented in beginner-friendly language. The platform features an automated PDF delivery system that sends comprehensive astronomy guides directly to users' email addresses, enabling offline learning.

Key features include:

\- Structured learning modules from novice to expert level

\- Detailed telescope and binocular selection guides

\- Practical observation technique tutorials

\- Automated PDF resource delivery via email

\- Comprehensive 40+ page astronomy education guide

\- Mobile-responsive web interface

\- Inspiring astronomical quotes and visuals

StellerAtlas aims to reduce the 73% beginner dropout rate in amateur astronomy by providing clear, accessible, and practical guidance that bridges the gap between curiosity and cosmic knowledge.

\---

\## Tech Stack

\### Frontend

\- \*\*HTML5\*\* - Semantic markup and structure

\- \*\*CSS3\*\* - Responsive styling and animations

\- \*\*JavaScript\*\* - Interactive UI components and client-side logic

\### Backend

\- \*\*Flask (Python)\*\* - RESTful API framework for server-side logic

\- \*\*SMTP (Simple Mail Transfer Protocol)\*\* - Email automation and delivery

\- \*\*SSL/TLS\*\* - Secure email transmission

\### Libraries & Frameworks

\- \*\*Flask-CORS\*\* - Cross-Origin Resource Sharing support

\- \*\*smtplib\*\* - Python standard library for SMTP protocol

\- \*\*email.message\*\* - Email content formatting and attachment handling

\### Infrastructure

\- \*\*Gmail SMTP Server\*\* - Email delivery service

\- \*\*Web Hosting\*\* - \[Specify your hosting platform\]

\### Development Tools

\- \*\*Python 3.x\*\* - Primary programming language

\- \*\*Git\*\* - Version control

\- \*\*VS Code / PyCharm\*\* - Development environment

\---

\## Dataset Used

\*\*No external datasets were used in this project.\*\*

The educational content is sourced from:

\- "Ready to Dive Deeper" - Astronomy basics comprehensive guide (included as PDF resource)

\- Original content created specifically for beginner astronomy education

\- Curated astronomy quotes and educational materials

\---

\## Installation & Setup

\`\`\`bash

\# Clone the repository

git clone https://github.com/\[your-username\]/stelleratlas.git

\# Navigate to project directory

cd stelleratlas

\# Create virtual environment

python -m venv .venv

\# Activate virtual environment

\# On Windows:

.venv\\Scripts\\activate

\# On macOS/Linux:

source .venv/bin/activate

\# Install dependencies

pip install flask flask-cors

\# Run the application

python scratch.py

\`\`\`

The application will start on \`http://localhost:5000\`

\---

\## Configuration

Update the email credentials in \`scratch.py\`:

\`\`\`python

smtp.login('your-email@gmail.com', 'your-app-password')

\`\`\`

\*\*Note:\*\* Use Gmail App Passwords for security. Never commit credentials to version control.

\---

\## Project Structure

\`\`\`

stelleratlas/

├── homepage.html # Main landing page

├── scratch.py # Flask backend server

├── ReadyToDiveDeeper.pdf # Educational resource

├── static/ # CSS, JS, images

├── templates/ # HTML templates

└── README.md # This file

\`\`\`

\---

\## Features

\- 📚 Comprehensive astronomy education content

\- 🔭 Equipment selection and observation guides

\- 📧 Automated PDF delivery system

\- 📱 Mobile-responsive design

\- ⚡ Fast loading and optimized performance

\- 🌟 Inspiring astronomical quotes and visuals

\---

\## Future Enhancements

\- Interactive 3D sky map with real-time positions

\- AI-powered personalized learning paths

\- Community platform for astronomy enthusiasts

\- Native mobile applications (iOS & Android)

\- Augmented reality sky viewing

\- Live telescope streaming integration

\---

\## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

\---

\---

\## Acknowledgments

\- InnoQuest Hackathon for the opportunity

\- Astronomy education resources and guides

\- Open-source community for tools and frameworks

\---

\*\*Made with ❤️ for astronomy enthusiasts worldwide\*\*