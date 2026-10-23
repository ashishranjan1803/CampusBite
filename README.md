🍔 CampusBite - Smart College Canteen Ordering System

CampusBite is a lightweight, responsive web application designed to help college students skip long cafeteria lines by pre-ordering food from their local campus canteen. Built with pure HTML, CSS, and vanilla JavaScript, it provides a seamless user experience for selecting colleges, browsing menus, building orders, and tracking preparation in real-time.

✨ Features

🎓 College Selection & Persistence:

Select from a comprehensive database of colleges across Karnataka by city.

Dynamically updates application headers, footers, and receipt details with your selected college.

Persists selected location across browser refreshes via localStorage.

🍴 Interactive Food Menu:

Clean grid layout featuring breakfast, fast food, beverages, and regional specialties.

Real-time search/browsing capabilities.

🛒 Dynamic Shopping Cart & Checkout:

Slide-out cart panel with real-time quantity adjustments and item deletion.

Total price and item count updates instantly.

Checkout input validation for student name, USN/ID, and pickup time.

⏱️ Real-Time Order Tracking & Live Queue:

Live canteen queue counter and estimated waiting time calculator.

Interactive status tracker (Order Placed ➔ Preparing ➔ Ready for Pickup).

Visual countdown timer for active orders.

📱 Mobile-First Responsive Design:

Modern, clean user interface optimized for desktop, tablet, and mobile displays.

🚀 Live Demo

Check out the live site here:

👉 CampusBite Live Application (or your updated Netlify link)

🛠️ Tech Stack

Frontend Structure: HTML5

Styling: Custom CSS3 (Flexbox & CSS Grid)

Logic & State: JavaScript (Vanilla JS, LocalStorage API)

Hosting / Deployment: Netlify

📁 Project Structure

├── index.html        # Single-file monolithic web application (HTML, CSS, JS)
└── README.md         # Project documentation


💻 Local Setup & Development

No complex node packages, dependencies, or build tools are required to run CampusBite!

Clone or Download the Repository:

git clone https://github.com/your-username/campusbite.git


Navigate into the Project Folder:

cd campusbite


Run the Application:

Open index.html directly in any modern web browser (Chrome, Firefox, Edge, Safari).

Or use a local development server like VS Code's Live Server extension.

🌐 Deploying to Netlify

Option 1: Netlify Drop (Fastest)

Visit drop.netlify.com.

Drag and drop the index.html file into the upload area.

Your site will immediately go live!

Option 2: Netlify CLI

npm install netlify-cli -g
netlify deploy --prod


📄 License

This project is open-source and available under the MIT License.
