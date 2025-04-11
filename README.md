# cpdb


# 🪙 Crypto Dashboard

A modern and interactive crypto dashboard built with **Next.js**, **TypeScript**, **Tailwind CSS**, and **Recharts**.

This dashboard displays real-time crypto metrics, charts, and a vault table using a clean and responsive UI.

---

## 🚀 Getting Started

Follow these steps to run the project locally.

### ✅ Prerequisites

- Node.js **v16.8+**
- npm or yarn

---

## 🛠️ Setup Instructions

### 1. Create a New Next.js Project

```bash
npx create-next-app crypto-dashboard
cd crypto-dashboard
```

When prompted, select:

- **TypeScript**: Yes  
- **ESLint**: Yes  
- **Tailwind CSS**: Yes  
- **`src/` directory**: No (optional)  
- **App Router**: Yes  
- **Import alias**: Yes (default `@/*`)  

---

### 2. Install Dependencies

```bash
npm install recharts lucide-react
# or
yarn add recharts lucide-react
```

---

### 3. Add the Project Code

You can:

- Use the "Add to codebase" button if available  
**OR**  
- Manually create the following files and copy the respective code into them:

```
components/
├── metrics-card.tsx
├── stats-chart.tsx
├── vault-table.tsx

app/
├── page.tsx
├── layout.tsx

styles/
└── globals.css
```

---

### 4. Run the Development Server

```bash
npm run dev
# or
yarn dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser 🚀

---

## 📊 Features

- Real-time crypto metrics display
- Interactive charts with Recharts
- Stylish table for vault data
- Fully responsive & clean UI
- Built with Next.js App Router and Tailwind

---

## 📁 Folder Structure (Simplified)

```
crypto-dashboard/
├── components/
│   ├── metrics-card.tsx
│   ├── stats-chart.tsx
│   └── vault-table.tsx
├── app/
│   ├── layout.tsx
│   └── page.tsx
└── styles/
    └── globals.css
```

---

## 📌 License

This project is open-source and available under the [MIT License](LICENSE).

