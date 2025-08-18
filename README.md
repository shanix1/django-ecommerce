🐺 Django E-Commerce Store — Success Wolf Edition
🚀 Elevator Pitch

🛒 Shop. Click. Pay. Repeat. Built with Django + Python, this full-stack e-commerce store brings the real-world shopping experience online. Browse products, add to cart, checkout seamlessly, and pay securely via PayPal 💳.

💡 Why it rocks:

Smooth responsive UI for all devices 📱

Full cart & order tracking system 📦

Admin panel for managing products, users, and orders ⚙️

Portfolio-ready — showcases full-stack web development skills 💻

Extensible & modular — easy to add coupons, reviews, or AI-powered recommendations 🔥

Perfect for learning, prototyping, or impressing clients. This isn’t just code — it’s a ready-to-run online store! 🐍✨
🛒 Django E-Commerce Store

An e-commerce store built with Django, supporting a variety of products, add-to-cart functionality, a full checkout process, and PayPal integration for payments. 💸

✨ Features

🛍 Product Catalog: Browse a wide selection of products.

➕ Add to Cart: Instantly add items to your cart and adjust quantities.

💳 Checkout: Seamless checkout flow with information gathering and order confirmation.

💰 Payments: Pay securely using PayPal.

📦 Order Tracking: Track purchased items and order statuses.

📱 Responsive UI: Built with HTML, CSS, and JavaScript for a smooth user experience.

⚙️ Admin Panel: Manage products, orders, and users via Django admin.

📸 Screenshots
🏪 Storefront
<img width="1355" height="654" alt="The store page in which items are present" src="https://github.com/user-attachments/assets/cbc645a9-ce42-4e4f-a795-687e12707f01" />

🛒 Add to Cart & Cart Overview
<img width="1335" height="602" alt="when we click on add to cart on item the small button on top right corner stores and increments and when we go inside the cart items have exact numbers thaT were stored and up down arrow " src="https://github.com/user-attachments/assets/429fb057-e69a-4725-bdac-fb7dc7737d94" />

📝 Checkout Process
<img width="1366" height="623" alt="checkout functionality takes us to gather or confirm our info for confirming the order" src="https://github.com/user-attachments/assets/6f48139e-588c-4c2e-b7b8-7ba2424d35e1" />

💳 Payment Integration
<img width="1359" height="583" alt="PAYPAL WORKING PROPERLY" src="https://github.com/user-attachments/assets/747b36ff-fa41-4d26-8487-ad2742465be8" />
<img width="1195" height="539" alt="PAYPAL WORKING PROPERLY1PNG" src="https://github.com/user-attachments/assets/bba1bb22-2b11-4480-a2fd-7baaea4e84b9" />
![WhatsApp Image 2025-08-01 at 14 19 09](https://github.com/user-attachments/assets/e1bf4fa8-a49e-42bd-98b6-a2692e4a2523)

✅ Payment Confirmation
<img width="1366" height="594" alt="when we authenticate our info , the paypal options appear for the payment and then order is confirmed" src="https://github.com/user-attachments/assets/127daaa8-cf9e-4c87-91f3-34efb1463865" />

🚀 Getting Started
🛠 Prerequisites
Python 3.8+ 🐍
pip 📦

⚡ Installation
  1. Clone the repository
   git clone https://github.com/shanix1/django-ecommerce.git
   cd django-ecommerce
  2. Create a virtual environment
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
  3. Install dependencies
   pip install -r requirements.txt
  4. Apply migrations
   python manage.py migrate
  5. Create a superuser (for admin access)
   python manage.py createsuperuser
  6. Run the development server
   python manage.py runserver
   
Visit 🌐 http://127.0.0.1:8000/ in your browser.

💳 PayPal Integration
  1. The project uses paypalrestsdk for payments.
  2. Configure your PayPal sandbox or live credentials in your Django settings. 🔑

🛠 Tech Stack
  1. Backend: Django (Python) 🐍
  2. Frontend: HTML, CSS, JavaScript 💻
  3. Payments: PayPal REST SDK 💸

📂 Directory Structure
“The backend project structure for the ecommerce app — with clean separation of concerns, static asset handling, and virtual environment properly scoped.” ✅
D:\
└── DJANGO WORKSPACE\
    └── IMPORTANT\
        └── django-ecommerce\
            ├── venv\                                ← virtual environment (outside base dir - GOOD ✅)
            └── src\                                 ← your Django BASE_DIR
                ├── manage.py
                ├── db.sqlite3

                ├── ecommerce\                        ← main settings folder
                │   ├── __pycache__\
                │   ├── __init__.py
                │   ├── settings.py
                │   ├── urls.py
                │   └── wsgi.py

                ├── store\                            ← your main app
                │   ├── __pycache__\
                │   ├── __init__.py
                │   ├── admin.py
                │   ├── apps.py
                │   ├── models.py
                │   ├── urls.py
                │   ├── views.py
                │   ├── utils.py                      ← ✅ custom logic utils file
                │   └── templates\
                │       └── store\
                │           ├── cart.html
                │           ├── checkout.html
                │           ├── main.html
                │           └── store.html

                ├── static\                           ← global static folder (perfectly placed 💯)
                │   ├── css\
                │   │   └── main.css
                │   ├── js\
                │   │   └── cart.js
                │   └── images\
                │       └── 12-product_images.png

📌 Requirements
  See requirements.txt:
    Django==5.2.5
    paypalrestsdk==1.13.3
    django-crispy-forms==2.4
    whitenoise==6.9.0
    # ...other dependencies
🤝 Contributing
  1. Fork the repo 🍴
  2. Create your feature branch (git checkout -b feature/FeatureName) 🌿
  3. Commit your changes (git commit -am 'Add new feature') 💾
  4. Push to the branch (git push origin feature/FeatureName) 🚀
  5. Create a pull request 🔗

📄 License
MIT 📝
