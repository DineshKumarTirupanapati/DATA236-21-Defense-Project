# DATA236-21-Defense-Project
E-Commerce Platform with Product Recommendation Engine

*Project Overview*
This project is a fully functional e-commerce platform integrated with a personalized recommendation engine. The system enhances user experience by providing product recommendations using TF-IDF vectorization and cosine similarity. Built with modern technologies such as Next.js, React.js, Node.js, and a Python-based recommendation system, the platform ensures scalability, dynamic interactivity, and efficient performance.

*Key Features*
E-Commerce Functionalities
Product browsing and details page.
Shopping cart and checkout process.
User authentication (login and signup pages).

*Recommendation Engine*
Content-based recommendations powered by TF-IDF and cosine similarity.
Personalized suggestions for users based on product attributes.
Fetch and display product data dynamically.

*Scalability*
The system runs locally with development deployment enabled via ngrok.

*File Structure*
ecommerce-nextjs-m
|
├── .next/                      # Next.js build directory
├── node_modules/               # Node.js dependencies
|
├── pages/                      # Next.js routing
│   ├── cart.js                 # Shopping cart page
│   ├── checkout.js             # Checkout page
│   ├── login.js                # Login page
│   ├── productpage.js          # Product details page
│   ├── recommended.js          # Recommendation page
│   ├── signup.js               # Signup page
│   ├── smartphone.js           # Smartphone products page
│   └── clearcart.js            # Clear cart functionality
|
├── public/                     # Static files and images
│   ├── aircooler.jpg           # Sample product images
│   ├── product-banner-1.jpg    # Banner images
│   └── ...                     # Additional images
|
├── src/                        # Source code
│   ├── app/                    # Application structure
│   │   ├── globals.css         # Global styles
│   │   ├── layout.tsx          # Layout for all pages
│   │   └── page.tsx            # Main frontend homepage
│   ├── components/             # Reusable components
│   │   ├── admin-panel/        # Admin interface components
│   │   ├── front-end/          # Frontend UI components
│   │   │   ├── Navbar.tsx      # Navigation bar
│   │   │   ├── Footer.tsx      # Footer component
│   │   │   ├── FeatureCard.tsx # Feature card
│   │   │   ├── TrendingProducts.tsx # Trending products section
│   │   │   └── ...             # Other UI components
│   ├── redux/                  # State management (Redux)
│   └── utils/                  # Utility functions
|
├── app.py                      # Python script for recommendation logic
├── server.js                   # Express server for API integration
├── recommendation_system.py    # Product recommendation system logic
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation

*Technologies Used*

*Frontend*
*Next.js:* Framework for server-side rendering and routing.
*React.js:* Component-based UI library.
*Tailwind CSS:* Utility-first CSS for responsive design.

*Backend*
*Node.js:* JavaScript runtime for backend services.
*Express.js:* Minimalist backend framework for API development.

*Recommendation Engine*
*Python:* Core logic for the recommendation system.
*TF-IDF and Cosine Similarity:* Content-based filtering techniques.
*Flask:* Lightweight web server for hosting the recommendation system.

*Deployment*
ngrok: Local deployment for testing and development.

*Setup and Installation*
*Step 1:* Clone the Repository

git clone https://github.com/your-username/ecommerce-nextjs-m.git
cd ecommerce-nextjs-m

*Step 2:* Install Node.js Dependencies

npm install

*Step 3:* Install Python Dependencies
Make sure Python is installed. Then run:

pip install -r requirements.txt

*Step 4:* Run the Recommendation System
Start the Python server for the recommendation engine:

python app.py

*Step 5:* Start the Next.js Application
Run the development server for the frontend:

npm run dev

*How It Works*

*Frontend*
Users navigate through the platform (products, cart, recommendations).
Components fetch data from the Express.js backend.

*Backend*
Node.js handles API requests and forwards user data to the recommendation system.

*Recommendation Engine*
The Python script processes product data using TF-IDF and cosine similarity.
Personalized recommendations are returned to the frontend.

*Future Enhancements*
Transition to a cloud-based deployment (e.g., GCP or AWS).
Integrate collaborative filtering for hybrid recommendations.
Add real-time feedback mechanisms for user interaction.
Implement advanced ML models for better accuracy.

*Contributors*
Dinesh Kumar Tirupanapati
Shanmukh Raj Siricilla
Venkata Nagasai Gautam Kasarbada
VEnkat Kiran Reddy Kota

*License*
This project is licensed under the MIT License.
