# 🌐 RDAP Lookup Tool

A sleek and user-friendly web interface for querying **domain registration data** using **RDAP (Registration Data Access Protocol).**  
Built with **HTML, JavaScript, and TailwindCSS**, featuring **collapsible JSON, improved UX, and real-time search.**

---

## 🚀 Features
✅ **Modern UI** – Styled with TailwindCSS for a clean look  
✅ **Real-Time Search** – Fetch RDAP data instantly  
✅ **Collapsible JSON** – Hide/show raw RDAP response  
✅ **Error Handling** – Displays errors clearly  
✅ **Mobile-Friendly** – Fully responsive design  

---

## 🔧 How It Works
1️⃣ Enter a **domain name** (e.g., `example.com`).  
2️⃣ Click **"Search"** to fetch RDAP data.  
3️⃣ View **formatted details** (registrar, status, expiration, etc.).  
4️⃣ Expand **raw JSON response** if needed.  

---

## 🎯 API Backend
This frontend queries the **RDAP Lookup API** running on Cloudflare Workers.  
👉 **Backend API Repo**: [rdap-lookup-api](https://github.com/m3lixir/rdap-lookup-api)  
👉 **API Endpoint**:  
```
https://icann-whois.melisasavich.workers.dev/api/rdap
```
Example API Request:
```
curl -X POST https://icann-whois.melisasavich.workers.dev/api/rdap \
     -H "Content-Type: application/json" \
     -d '{"domain": "example.com"}'
```

---

## 📦 Tech Stack
- **Frontend**: HTML, JavaScript, TailwindCSS  
- **Backend API**: Cloudflare Workers ([rdap-lookup-api](https://github.com/m3lixir/rdap-lookup-api))  

---

## 🚀 Live Demo
[🔗 Try RDAP Lookup](https://icann-whois.pages.dev)  

---

## 📄 Setup & Usage
Clone the repo:
```
git clone https://github.com/m3lixir/rdap-lookup.git
cd rdap-lookup
```
Run it locally:
```
open index.html
```

---

## 👨‍💻 Contributing
1. **Fork the repo**
2. Create a new branch:  
   ```
   git checkout -b feature-new-ui
   ```
3. Commit your changes:  
   ```
   git commit -m "feat: add dark mode toggle"
   ```
4. Push and open a PR 🚀  

---

## 📜 License
This project is open-source under the **MIT License**.  

---

💡 **Have ideas? Want to improve it?** Feel free to submit PRs! 🚀  
🔥 Built with love by [Melisa K. Savich](https://melisasavich.com).
