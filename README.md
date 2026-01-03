# 🎬 CinePlix – Mobile Movie App

[![React Native](https://img.shields.io/badge/React%20Native-0.81.5-blue)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-Managed-orange)](https://expo.dev/)
[![Appwrite](https://img.shields.io/badge/Appwrite-Cloud-purple)](https://appwrite.io/)
[![Tailwind](https://img.shields.io/badge/TailwindCSS-3.5-teal)](https://tailwindcss.com/)

CinePlix is a **React Native mobile movie app** built with **Expo, Appwrite, Tailwind, and NativeWind**.  
It allows users to **browse, search, and track trending movies** in real-time with a smooth, mobile-first UI.

---

## 🌟 Features

- **Real-time data**: Fetch and display movies dynamically using Appwrite
- **Home Page**: Featured and discover movies
- **Search Page**: Find your favorite movies quickly
- **Trending movies**: Popularity algorithm tracks searches to display trending content
- **Mobile-first UI**: Responsive design with Tailwind & NativeWind

---

## 🛠 Tech Stack

| Feature            | Tech                             |
| ------------------ | -------------------------------- |
| Mobile Framework   | React Native (Expo)              |
| Backend / Database | Appwrite                         |
| Styling            | Tailwind CSS + NativeWind        |
| Real-time Data     | Appwrite Database & Queries      |
| Navigation         | React Navigation                 |
| State Management   | React Hooks / Zustand (optional) |
| Movie API          | TMDB / Your Movie API Key        |

---

## ⚙️ Environment Setup

1. **Clone the repo:**

```bash
git clone <YOUR_REPO_URL>
cd CinePlix

```

---

2. **Install dependencies:**

```bash
npm install
# or
yarn install

```

**Dependencies include**:

- react-native
- expo
- nativewind
- tailwindcss
- react-native-masked-view
- react-native-linear-gradient
- react-native-appwrite
- react-navigation

---

3. **Environment Variables:**

**Create a .env file in the root directory:**:

```bash
EXPO_PUBLIC_MOVIE_API_KEY=your_movie_api_key_here
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_project_id_here
EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_database_id_here
EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_collection_id_here

```

4. **Start the app:**

**Create a .env file in the root directory:**:

```bash
EXPO_PUBLIC_MOVIE_API_KEY=your_movie_api_key_here
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_project_id_here
EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_database_id_here
EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_collection_id_here

```

---

## SnapShots 📷

![CinePlix Home](https://res.cloudinary.com/duju3bhds/image/upload/v1767447786/Screenshot_2026-01-03-19-10-42-879_host.exp.exponent_es9brg.jpg)
![Search](https://res.cloudinary.com/duju3bhds/image/upload/v1767447786/Screenshot_2026-01-03-19-11-13-311_host.exp.exponent_yofcjs.jpg)
![Movie Details](https://res.cloudinary.com/duju3bhds/image/upload/v1767447786/Screenshot_2026-01-03-19-11-04-065_host.exp.exponent_w6m0k2.jpg)





---

## Future Enhancements ✨

- Add user authentication for saving favorites
- Push notifications for trending movies
- Improve offline support with local caching