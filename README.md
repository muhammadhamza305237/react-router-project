# 🧭 React Router Multi-Page App

A multi-page web application built with **React 19**, **React Router DOM**, **Tailwind CSS v4**, and **Vite**, demonstrating nested layouts, active navigation links, dynamic route parameters, and route loader data fetching.

**Live Demo:** https://react-router-project-kohl.vercel.app

## 🛠️ Tech Stack
- **Frontend:** React 19, Vite
- **Routing:** React Router DOM (`createBrowserRouter`, `createRoutesFromElements`, `RouterProvider`, `Outlet`, `Link`, `NavLink`, `useParams`, `loader`, `useLoaderData`)
- **Styling:** Tailwind CSS v4 (`@tailwindcss/vite`)

## ✨ Key Features
- **Persistent Layout & Nested Routes:** Shared `Header` and `Footer` inside `Layout` with dynamic view rendering via `<Outlet />` across `/`, `/about`, `/contact`, `/user/:userid`, and `/github`.
- **Active Route Highlighting:** Uses `NavLink` active state styling in the header navigation bar.
- **Dynamic URL Parameters:** Reads `:userid` from the route path via `useParams()` on the User page.
- **Route Loader Data Fetching:** Loads GitHub profile data through a React Router `loader` function and consumes it with `useLoaderData()`.

## 🚀 How to run locally
1. Clone the repository
2. Run `npm install`
3. Run `npm run dev`