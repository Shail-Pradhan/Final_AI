## 🚀 Deploy AI Complaint System on Render (Beginner Friendly)

Follow this quick guide to deploy both the **backend** and **frontend** of the app using [Render](https://render.com).

**What is Render?**  

[Render](https://render.com) is a cloud platform that lets you host full-stack web apps for free. It supports automatic deployments from GitHub, making it super easy for beginners to launch web apps without managing servers.
---

### 🛠 1. Backend (API Server)

#### 🔁 Fork this Repo
👉 [https://github.com/Shail-Pradhan/Final_AI](https://github.com/Shail-Pradhan/Final_AI)

Click **Fork** on the top right.

#### ⚙️ Set Up on Render

1. Go to [Render Dashboard](https://dashboard.render.com)
2. Click **"New" → "Web Service"**
3. Connect your GitHub and select your forked repo

#### 🧾 Use These Settings:

| Setting           | Value                          |
|-------------------|---------------------------------|
| Name              | `AIComplaintApp`               |
| Branch            | `main`                         |
| Root Directory    | `AIComplaintBackend`           |
| Dockerfile Path   | `AIComplaintBackend/Dockerfile`|
| Instance Type     | `Free`                         |
| Auto Deploy       | ✅ On Commit                   |

Click **Create Web Service** and wait for deployment.

---

### 🌐 2. Frontend (User Interface)

#### 🧾 Set Up Static Site on Render

1. On the same Render dashboard, click **"New" → "Static Site"**
2. Choose the **same GitHub repo** and branch

#### ⚙️ Use These Settings:

| Setting           | Value             |
|-------------------|-------------------|
| Name              | `ComplaintAIApp`  |
| Branch            | `main`            |
| Root Directory    | `Frontend`        |
| Publish Directory | `Frontend/`       |
| Build Command     | *(leave blank)*   |
| Auto Deploy       | ✅ On Commit      |

Click **Create Static Site** and your frontend will go live!

---

### ✅ That’s it!

Now both your **frontend** and **backend** will auto-deploy every time you push to the `main` branch. 🎉

