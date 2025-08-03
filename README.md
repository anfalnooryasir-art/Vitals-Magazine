# Vitals Magazine

**Vitals Magazine** is a modern online magazine built using:

- [Next.js](https://nextjs.org) — React framework
- [Tailwind CSS](https://tailwindcss.com) — Utility-first CSS
- [Sanity CMS](https://www.sanity.io) — Headless content management
- [FlipHTML5](https://fliphtml5.com) — PDF flipbook embedding
- [Vercel](https://vercel.com) — Free hosting

---

## 📖 Features

- ✨ Beautiful homepage, about, contact, and issues pages
- 📚 All magazine issues listed and individually linked
- 📄 Embedded flipbook readers using FlipHTML5
- 🧑‍💻 Content editable by non-developers using Sanity Studio
- 📱 Fully responsive design for all devices

---

## 🚀 How to Use

### 1. Install dependencies

```bash
npm install
```

### 2. Run the development server

```bash
npm run dev
```

Visit `http://localhost:3000` in your browser.

---

## 🧠 Sanity CMS Setup

1. Install Sanity CLI:
```bash
npm install -g @sanity/cli
```

2. Initialize studio:
```bash
sanity init
```

3. Add the issue schema (see `/studio/schemas/issue.js`)

4. Start the Sanity Studio:
```bash
sanity start
```

---

## 🌐 Deployment

- Push to GitHub
- Connect to Vercel
- Add Sanity project ID and dataset to Vercel environment variables:
  ```
  NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
  NEXT_PUBLIC_SANITY_DATASET=production
  ```

---

## ✉️ Contact

Email: contact@vitalsmagazine.com  
Website: [vitalsmagazine.com](https://vitalsmagazine.com)

