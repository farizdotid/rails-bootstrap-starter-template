## 📌 Rails Bootstrap Starter Template

🚀 A ready-to-use **Rails Starter Template** with **Bootstrap** preconfigured. Clone, install dependencies, and start building your Rails app with a modern UI instantly!

---

## ⚡ Features

✅ Preconfigured **Bootstrap** (via Importmaps/Vite/esbuild - specify which one)  
✅ Clean **Rails 8** setup  
✅ Ready-to-use layouts and components  
✅ Developer-friendly setup  

---

## 📦 Installation

```bash
git clone https://github.com/farizdotid/rails-bootstrap-starter-template.git
cd rails-bootstrap-starter
bundle install
rails db:setup
rails s
```

👀 Open your browser and visit: [http://localhost:3000](http://localhost:3000)

---

## 🎨 Customization

Modify the Bootstrap configuration in:  
```bash
app/assets/stylesheets/application.bootstrap.scss
```

If you're using **esbuild** or **Vite**, update Bootstrap imports inside:  
```bash
app/javascript/application.js
```

---

## 📂 Project Structure

```
📦 rails-bootstrap-starter
 ┣ 📂 app
 ┃ ┣ 📂 assets
 ┃ ┃ ┣ 📂 stylesheets  # Bootstrap styles
 ┃ ┃ ┣ 📂 javascript   # JS setup (if using esbuild/Vite)
 ┃ ┃ ┗ 📂 images
 ┃ ┣ 📂 views
 ┃ ┃ ┗ 📂 layouts      # Application layout with Bootstrap
 ┃ ┣ 📂 controllers
 ┃ ┗ 📂 models
 ┣ 📂 config
 ┣ 📜 Gemfile
 ┣ 📜 package.json     # (if applicable)
 ┗ 📜 README.md
```

---

## 🔥 Contributing

Feel free to **fork** this project and make improvements! PRs are welcome.

---

## 📜 License

MIT License. Free to use and modify.
