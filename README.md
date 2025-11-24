Quora Clone – CRUD App (Node.js + Express + EJS)
A simple Quora-style CRUD web application where users can create, read, update, and delete posts — built WITHOUT any database.
Data is stored using a simple in-memory array / JSON file, making it perfect for beginners learning CRUD and REST APIs.

🚀 Features
📝 Posts:
Create a new post,
View all posts,
View a single post in detail,
Edit post,
Delete post.

🎨 UI (EJS)
Clean EJS templates,
Styled using basic CSS,
Shows username (example: @nidhi),
Simple layout similar to Quora Posts.

🛠️ Tech Stack
Node.js,
Express.js,
EJS,
CSS,
No database used (no MongoDB / SQL).

🔌 RESTful Routes:
📥 GET:
/posts — Show all posts.
/posts/new — Form to create a new post.
/posts/:id — Show a single post.
/posts/:id/edit — Edit form.

➕ POST:
/posts — Create a post.

✏️ PATCH / PUT:
/posts/:id — Update a post.

❌ DELETE:
/posts/:id — Delete a post.

▶️ How to Run the Project:
1️⃣ Install dependencies:
npm install
2️⃣ Start the server:
npm start
3️⃣ Open in browser:
http://localhost:8080/posts

Author:Nidhi
Learning full-stack Web Dev and building mini projects 💛
