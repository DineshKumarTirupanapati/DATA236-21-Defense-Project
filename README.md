# DATA236-21-Defense-Project
#E-Commerce Platform with Product Recommendation Engine

#*Project Overview*
This project is a fully functional e-commerce platform integrated with a personalized recommendation engine. The system enhances user experience by providing product recommendations using TF-IDF vectorization and cosine similarity. Built with modern technologies such as Next.js, React.js, Node.js, and a Python-based recommendation system, the platform ensures scalability, dynamic interactivity, and efficient performance.

#*Key Features*
E-Commerce Functionalities
Product browsing and details page.
Shopping cart and checkout process.
User authentication (login and signup pages).

#*Recommendation Engine*
Content-based recommendations powered by TF-IDF and cosine similarity.
Personalized suggestions for users based on product attributes.
Fetch and display product data dynamically.

#*Scalability*
The system runs locally with development deployment enabled via ngrok.

# E-Commerce Platform with Product Recommendation Engine

## Project Structure

# E-Commerce Platform with Product Recommendation Engine

## Project Structure

```plaintext
ecommerce-nextjs-m
|
├── .next/                      
│   Next.js build directory
|
├── node_modules/               
│   Node.js dependencies
|
├── pages/                      
│   Next.js routing
│   ├── cart.js                 
│       Shopping cart page
│   ├── checkout.js             
│       Checkout page
│   ├── login.js                
│       Login page
│   ├── productpage.js          
│       Product details page
│   ├── recommended.js          
│       Recommendation page
│   ├── signup.js               
│       Signup page
│   ├── smartphone.js           
│       Smartphone products page
│   └── clearcart.js            
│       Clear cart functionality
|
├── public/                     
│   Static files and images
│   ├── aircooler.jpg           
│       Sample product images
│   ├── product-banner-1.jpg    
│       Banner images
│   └── ...                     
│       Additional images
|
├── src/                        
│   Source code
│   ├── app/                    
│       Application structure
│       ├── globals.css         
│           Global styles
│       ├── layout.tsx          
│           Layout for all pages
│       └── page.tsx            
│           Main frontend homepage
│   ├── components/             
│       Reusable components
│       ├── admin-panel/        
│           Admin interface components
│       ├── front-end/          
│           Frontend UI components
│           ├── Navbar.tsx      
│               Navigation bar
│           ├── Footer.tsx      
│               Footer component
│           ├── FeatureCard.tsx 
│               Feature card
│           ├── TrendingProducts.tsx 
│               Trending products section
│           └── ...             
│               Other UI components
│   ├── redux/                  
│       State management (Redux)
│   └── utils/                  
│       Utility functions
|
├── app.py                      
│   Python script for recommendation logic
├── server.js                   
│   Express server for API integration
├── recommendation_system.py    
│   Product recommendation system logic
├── requirements.txt            
│   Python dependencies
└── README.md                   
    Project documentation

