# Secret-project

🔐 PasswordCheck

A simple Node.js Express app that demonstrates basic authentication middleware using a password check. If the correct password is provided, the user gains access to a secret page.

✨ Features

1.Middleware-based password authentication

2.Request body parsing with body-parser

3.Simple HTML pages for login and secret content

4.Easy to run on local server
Demonstrates Express.js fundamentals

🖼 Demo Flow

Open http://localhost:3000/

Enter the password (ILoveProgramming)

If correct → Secret page unlocks

If incorrect → Redirects back to index page


🛠 Tech Stack

Node.js

Express.js

body-parser

Path

⚡ Getting Started

📥 Installation

Clone the repository and install dependencies:

git clone https://github.com/your-username/password-check.git

cd password-check

npm install

▶ Run the App
node solution.js

Your app will run at:
👉 http://localhost:3000

📂 File Structure
.
├── public
│   ├── index.html      # Login Page

│   ├── secret.html     # Secret Page (protected)

├── solution.js         # Express App

└── package.json        # Dependencies

🚀 How It Works
Middleware passwordCheck validates the password.

Correct password: grants access to secret.html.

Wrong password: redirects to index.html.
