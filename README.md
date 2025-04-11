
# 🪙 Crypto Dashboard

A **modern**, **interactive**, and **feature-rich** crypto dashboard built with **Next.js**, **TypeScript**, **Tailwind CSS**, **Recharts**, and **Analog Buttons**. This project allows users to visualize crypto metrics, charts, and vault data with an intuitive UI, enhanced by stylish analog buttons for interactive control.

---

## 🚀 Getting Started

Follow the steps below to get the project running on your local machine.

### ✅ Prerequisites

- **Node.js v16.8+**
- **npm** or **yarn**

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
npm install recharts lucide-react react-analog-clock
# or
yarn add recharts lucide-react react-analog-clock
```

---

### 3. Add the Code to Your Project

You can:

- Use the "Add to codebase" button (if available)  
**OR**  
- Manually create the following files and copy the respective code into them:

```
components/
├── metrics-card.tsx
├── stats-chart.tsx
├── vault-table.tsx
├── analog-button.tsx  # For analog control buttons

app/
├── page.tsx
├── layout.tsx

styles/
└── globals.css
```

### 4. Run the Development Server

```bash
npm run dev
# or
yarn dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser 🚀

---

## 📊 Features

- **Real-time Crypto Metrics**: Dynamic updates of crypto data.
- **Interactive Charts**: Powered by **Recharts**, with smooth animations and transitions.
- **Vault Table**: Displays live data on your vault holdings.
- **Analog Buttons**: Includes stylish **analog clock buttons** for controlling aspects of the dashboard, providing a unique, interactive UI for navigating the dashboard.
- **Responsive & Clean UI**: Built with **Tailwind CSS** to ensure great performance on all screen sizes.
- **TypeScript Support**: Enhanced code quality and type-safety.

---

## 📁 Folder Structure (Simplified)

```
crypto-dashboard/
├── components/
│   ├── metrics-card.tsx
│   ├── stats-chart.tsx
│   ├── vault-table.tsx
│   └── analog-button.tsx  # New Analog Button component
├── app/
│   ├── layout.tsx
│   └── page.tsx
└── styles/
    └── globals.css
```

---

## 🧑‍💻 Tech Stack

- **Next.js**: A powerful React framework for building fast and scalable web applications.
- **TypeScript**: Adds static types to JavaScript for better code quality and safety.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI design.
- **Recharts**: A composable charting library built on React, perfect for displaying crypto metrics and real-time data.
- **Lucide-react**: A set of open-source, simple icons for your React applications.
- **Analog Clock Button**: A visually striking analog button control built using **react-analog-clock**, giving the dashboard a unique look and feel.

---

## 👨‍💻 Contributing

We welcome contributions to improve the project. To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-xyz`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add feature xyz'`)
5. Push to your branch (`git push origin feature-xyz`)
6. Create a new Pull Request

Please make sure your code follows the project's code style and passes all linting and testing checks.

---

## 📌 License

This project is open-source and available under the [MIT License](LICENSE).

