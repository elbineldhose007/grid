# 🖼️ Tailwind CSS Image Grid Layout

A responsive **image gallery grid layout** built using **HTML** and **Tailwind CSS**.
This project demonstrates how to create a modern **grid-based photo gallery** with different image spans using Tailwind utility classes.

---

## 📌 Features

* Responsive **CSS Grid layout**
* Built using **Tailwind CSS**
* Mixed grid sizes using:

  * `col-span`
  * `row-span`
* Clean **square image layout**
* Rounded image corners
* Simple and lightweight structure

---

## 🛠️ Technologies Used

* **HTML5**
* **Tailwind CSS (via CDN)**
* **Unsplash Images**

---

## 📂 Project Structure

```
project-folder
│
├── index.html
└── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/tailwind-image-grid.git
```

### 2️⃣ Open the project

Simply open the `index.html` file in your browser.

```bash
cd tailwind-image-grid
open index.html
```

No build tools or installations required since **Tailwind CDN** is used.

---

## 📸 Grid Layout Overview

The gallery uses **CSS Grid** with:

```
grid-cols-4
gap-2
```

Some images span multiple rows and columns to create a **dynamic masonry-style layout**.

Example:

```html
class="col-span-2 row-span-2 aspect-square"
```

This makes the image **occupy 2 columns and 2 rows**.

---

## 🎨 Tailwind Classes Used

| Class           | Purpose                  |
| --------------- | ------------------------ |
| `grid`          | Enables CSS Grid         |
| `grid-cols-4`   | Creates 4 columns        |
| `gap-2`         | Space between grid items |
| `aspect-square` | Keeps images square      |
| `rounded-xl`    | Rounded corners          |
| `col-span-2`    | Image spans 2 columns    |
| `row-span-2`    | Image spans 2 rows       |
| `min-h-screen`  | Full viewport height     |

---

## 📷 Image Source

All images are sourced from **Unsplash** for demo purposes.

---

## 💡 Possible Improvements

* Add **hover effects**
* Implement **lightbox preview**
* Make the grid **fully responsive**
* Add **lazy loading**
* Convert into a **React component**

---

## 📄 License

This project is open-source and free to use for learning purposes.

---

## 👨‍💻 Author

Created by **ELbin**

