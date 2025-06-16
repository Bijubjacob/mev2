
# 🌐 Biju Jacob - Resume Website

This is a personal resume site for **Biju Jacob**, created with HTML5 and Bootstrap. It’s fully responsive, includes a contact form (Formspree), and is hosted using **Azure Static Web Apps**.

## 📁 Project Structure

```

resume-website/
│
├── index.html          # Main HTML content
├── /mev2/Biju.jpg      # Profile image
└── README.md           # This file

````

## 🚀 Deployment on Azure Static Web Apps

### ✅ Prerequisites

- [Azure account](https://portal.azure.com/)
- [GitHub account](https://github.com/)
- Repo contains `index.html` at the root

### 🔧 Steps to Deploy

1. **Push your code to GitHub**  
   If your resume site isn't already on GitHub, initialize and push it:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/Bijubjacob/mev2.git
   git push -u origin main
````

2. **Go to Azure Portal**
   Search for **“Static Web Apps”** → Click **“Create”**.

3. **Fill in Details**:

   * **App name**: `biju-resume`
   * **Region**: Pick one close to you (e.g., East US)
   * **GitHub**: Authorize and connect your repo
   * **Build details**:

     * **Build Presets**: *Custom*
     * **App Location**: `/` (root)
     * **Api Location**: *(leave blank)*
     * **Output Location**: `/` (root)

4. **Click “Review + Create”**
   Azure will auto-generate a GitHub Actions workflow to build and deploy your app on every push to `main`.

5. **Wait for Deployment (\~1–2 mins)**
   Once done, Azure gives you a public URL like:

   ```
   https://orange-wave-0a2f93210.6.azurestaticapps.net
   ```


```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

## 🔒 Security Tips

* Never include sensitive credentials or secrets in HTML.
* Use CAPTCHA or honeypots for public contact forms if needed.

## 🧰 Tech Stack

* HTML5, CSS (inlined)
* Bootstrap 5.3 via CDN
* Azure Static Web Apps

---

🧑‍💻 Created by [Biju Jacob](mailto:BijuBJacob@lewisu.edu)

```

---
