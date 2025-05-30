# 🧳 React Packing List

A simple React app for managing a travel packing list. Users can add, check, and delete items to prepare for trips with ease.

## ✨ Features

- Add items with quantity and name
- Mark items as packed or unpacked
- Delete individual items or clear all
- Responsive and minimal UI

## 🚀 Demo

You can try a live demo here: [Demo Link](https://travel-list-nu-seven.vercel.app/) 

## 🛠️ Technologies Used

- **React** (Create React App)
- **JavaScript (ES6+)**
- **CSS**

## 📦 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/FarahAkl/travel-list.git
cd travel-list
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the app

```bash
npm start
```

### 4. Build for production

```bash
npm run build
```

## 📁 Project Structure

```bash
src/
├── components/
│   ├── PackingList.js
│   └── Form.js
│   └── Item.js
│   └── Stats.js
│   └── Logo.js
├── App.js
├── index.js
└── index.css
```

## 📝 Example Item Structure

```js
{
  id: 1,
  name: "Toothbrush",
  quantity: 2,
  packed: false
}
```
