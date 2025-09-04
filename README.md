# 📂 Dropbox Clone

A modern **Dropbox-inspired file storage application** built with **Next.js 14, TypeScript, Tailwind CSS, and Firebase**.  
This app provides secure authentication, drag-and-drop file uploads, file management (rename/delete), and a responsive dashboard UI with light/dark mode support.

---

## 🚀 Features

- 🔐 **Authentication with Clerk** (sign-in, sign-up, middleware protection)
- 📤 **File Upload** with drag & drop support (React Dropzone + Firebase Storage)
- 📂 **File Management** – rename, delete, sort, and view files
- 🎨 **Modern UI** – Tailwind CSS, shadcn/ui, Radix UI, dark/light mode
- ⚡ **State Management** – Zustand for modals & UI states
- 📊 **Table View** of files with TanStack React Table
- 🔔 **Notifications** with React Hot Toast
- ⏳ **Skeleton loaders** for smooth UI transitions
- 🌐 **Deployed on Vercel** with custom domain (Hostinger)

---

## 🛠 Tech Stack

**Frontend:**

- [Next.js 14](https://nextjs.org/)
- [React 18](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/) + [Radix UI](https://www.radix-ui.com/)

**Authentication:**

- [Clerk](https://clerk.com/)

**Backend & Database:**

- [Firebase](https://firebase.google.com/)
- [Firestore Database](https://firebase.google.com/docs/firestore)

**Utilities & Libraries:**

- Zustand (state management)
- React Dropzone (drag & drop uploads)
- React Hot Toast (notifications)
- TanStack React Table (table view)
- Pretty-bytes (file size formatting)

---

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/fawazv/Dropbox-clone.git
   cd dropbox-clone
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**  
   Create a `.env.local` file in the root and configure:

   ```env
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key

   NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_firebase_app_id
   ```

4. **Run the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📂 Project Structure

```
dropbox-clone/
├── app/                # Next.js App Router pages & layouts
├── components/         # Reusable UI components
├── lib/                # Firebase, utils, and helper functions
├── store/              # Zustand store for state management
├── styles/             # Tailwind CSS and global styles
├── public/             # Static assets
├── package.json
└── README.md
```

---

## 🚀 Deployment

This project is optimized for **Vercel deployment**:

1. Push your project to GitHub/GitLab.
2. Connect repository on [Vercel](https://vercel.com/).
3. Add environment variables in the Vercel dashboard.
4. Deploy 🚀

Optional: Configure a **custom domain via Hostinger**.

---

## 📸 Screenshots

### 🔐 Authentication with Clerk

<img src="/public/screens/auth.png" alt="Auth Page" width="600"/>

### 📂 File Dashboard

<img src="/public/screens/dashboard.png" alt="Dashboard" width="600"/>

---

## 📜 License

This project is licensed under the **MIT License** – you are free to use, modify, and distribute.

---

## 🙌 Acknowledgements

- [Clerk](https://clerk.com/) for authentication
- [Firebase](https://firebase.google.com/) for backend & storage
- [shadcn/ui](https://ui.shadcn.com/) for beautiful components
- [Vercel](https://vercel.com/) for hosting
- Inspired by Dropbox ✨
