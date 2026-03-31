# WordPress Automation Setup (Playwright)

## ✅ Prerequisites

Please ensure the following are installed:

* Visual Studio Code (or any IDE)
* Docker
* Node.js (v18 or above)
* Github access

---

# 🐳 WordPress Docker Setup

## 📥 Clone this project

```bash
git clone https://github.com/balajikrishnannewsuk/wordpress-local.git
```

## 📂 Move into project directory

```bash
cd wordpress-local
```

---

## 🚀 Run the project

```bash
docker-compose up -d
```

---

## 🌐 Access WordPress

* Site: http://localhost:8080
* Admin: http://localhost:8080/wp-admin

---

## 🔐 Initial WordPress Setup

After opening the admin panel:

http://localhost:8080/wp-admin/

You will see the WordPress setup screen.

Fill in the following details:

* **Site Title** → Your website name
* **Username** → Admin login username
* **Password** → Strong password
* **Email** → Your email address

Click **Install WordPress**.

---

## ✅ Login to Admin

After installation, log in at:

http://localhost:8080/wp-admin/

Use the username and password you created.

---

# 📋 Task Scenario (Playwright Automation)

Using Playwright, automate the following:

---

## ✅ Create Post

1. Login to WordPress admin
2. Navigate to **Posts → Add New**
3. Create a new post:

   * Title: `Test Automation Post`
   * Content: `Created via automation`
4. Publish the post

### ✔️ Verify

* “Post published” message is displayed
* Post is visible on the frontend

---

## 🗑️ Delete Post

1. Delete the created post

### ✔️ Verify

* “Post deleted” (or moved to trash) message
* Post is NOT visible on the frontend

---

