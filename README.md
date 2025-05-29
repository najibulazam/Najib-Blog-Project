# 📝 Najib Blog Site

**Najib Blog Site** is a dynamic and user-friendly blogging platform built with Django. It allows users to create, edit, and delete blog posts with image upload capabilities and content categorization. The project also features user authentication and a responsive UI built with Bootstrap.

## 🚀 Features

* 🧑‍💻 **User Authentication**

  * Secure signup, login, and logout functionality.

* ✍️ **Blog Post Management**

  * Full CRUD operations (Create, Read, Update, Delete) for blog posts.

* 🖼️ **Image Upload Support**

  * Upload images with blog posts using Pillow and Django's media handling.

* 🗂️ **Category Filtering**

  * Filter posts by categories for improved content organization.

* 📱 **Responsive Design**

  * Built with Bootstrap to ensure a clean, mobile-friendly interface.

## 🛠️ Tech Stack

* **Backend:** Django
* **Frontend:** HTML, CSS (Bootstrap), JavaScript
* **Database:** SQLite (default for development)
* **Image Handling:** Pillow

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/najibulazam/najib-blog-site.git
   cd najib-blog-site
   ```

2. **Create a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**

   ```bash
   python manage.py migrate
   ```

5. **Run the development server**

   ```bash
   python manage.py runserver
   ```

6. Visit `http://127.0.0.1:8000/` to use the blog site.

## 🖼️ Screenshots

*Add screenshots or GIFs showcasing the key features here.*

## 📂 Folder Structure

```

najib-blog-site/
├── blog/             # Blog app
├── media/            # Uploaded images
├── static/           # Static files (CSS, JS)
├── templates/        # HTML templates
├── najib_blog_site/  # Project settings
├── manage.py
```

## ✅ Future Improvements

* Add comment functionality
* Pagination for posts
* Tag support
* Rich text editor for post content

---

Let me know if you want to add deployment instructions (e.g., for Heroku or Vercel) or a custom logo/banner!
