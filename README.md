# Zhenggang Zhu Page Website

This is the official website for Zhenggang Zhu's research page at UC San Diego, hosted on **GitHub Pages**.

## 🌍 Live Website
🔗 **[Visit the website](https://wujialai106.github.io/zhengganglab/)**

## 📂 Project Structure
```
zhengganglab/
│── _config.yml       # Jekyll configuration file
│── _pages/           # Markdown pages
│── _includes/        # Reusable HTML components
│── _layouts/         # HTML layouts
│── _sass/            # SCSS stylesheets
│── assets/css/       # Compiled CSS files
│── assets/js/        # JavaScript files
│── images/           # Image assets
│── index.html        # Homepage
│── README.md         # Project Documentation
```

## 🚀 Deployment on GitHub Pages
This website is deployed via **GitHub Pages** using the `gh-pages` branch.

### How to Enable GitHub Pages:
1. Go to **Settings** → **Pages**.
2. Under **Build and Deployment**, select:
   - **Source:** `Deploy from a branch`
   - **Branch:** `gh-pages`
   - **Directory:** `/ (root)`
3. Click **Save**.
4. Wait for 1-2 minutes for the site to be deployed.
5. Visit: `https://wujialai106.github.io/zhengganglab/`

## 💻 Running Locally
If you want to test the website locally before deploying, follow these steps:

### **1️⃣ Install Jekyll & Dependencies**
```bash
# Install Jekyll and Bundler (if not installed)
gem install jekyll bundler
```

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/wujialai106/zhengganglab.git
cd zhengganglab
```

### **3️⃣ Install Dependencies**
```bash
bundle install
```

### **4️⃣ Run the Jekyll Server**
```bash
bundle exec jekyll serve
```
🔹 Now, open **http://localhost:4000/zhengganglab/** in your browser.

## 🛠 Troubleshooting
If you encounter issues, try the following:
- **Check Jekyll Errors:** Run `bundle exec jekyll build` to identify problems.
- **Trigger GitHub Pages Deploy:**
  ```bash
  git commit --allow-empty -m "Trigger GitHub Pages"
  git push origin gh-pages
  ```
- **Check GitHub Actions Logs:** If the website doesn’t update, check **GitHub Actions** under the **"Actions"** tab for any errors.

## 📜 License
This project is licensed under the MIT License.

---
✉️ **For any issues or suggestions, please open an issue in the repository.**


