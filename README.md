# Calixy

**Calixy** is a mobile application built with [Expo](https://expo.dev/) and React Native. Its goal is to support users in maintaining a healthy lifestyle by helping them:

- Log meals and track daily calorie intake  
- Record workouts and physical activity  
- View daily, weekly, and monthly statistics  

## Project Status

This project is currently under active development. I'm working on the core features and app structure. The code is regularly updated as the development progresses.

## Technologies

- React Native  
- Expo  
- TypeScript (planned)  
- Local Storage / SQLite (planned)  

## Why this project?

I’m building Calixy to improve my skills as a mobile developer while creating a useful tool for real-life health tracking. This project allows me to work on state management, mobile navigation, UI/UX design, and offline data handling.

## Roadmap (Nutrition Module)

### 🔹 Phase 1 – Basic Structure & Static Data

- [x] Initialize project with Expo and React Native
- [ ] Create static view to display calorie data (mocked for one day)
- [ ] Design basic UI for daily overview (total calories, list of meals)

### 🔹 Phase 2 – State Management & Mocked Logic

- [ ] Set up Redux for global state management
- [ ] Replace static data with simulated local "database" (in-memory object)
- [ ] Implement logic to calculate total calories based on meals
- [ ] Add form to input meals (name + calories)
- [ ] Update daily calorie total in real-time when meals are added

### 🔹 Phase 3 – Date-based Tracking

- [ ] Add display of current date and calories for that day
- [ ] Implement calendar view to navigate and select dates
- [ ] Show history of meals and total calories per selected day

### 🔹 Phase 4 – Persistence & Navigation

- [ ] Integrate SQLite to store meals and calories locally
- [ ] Test data loading and saving across sessions
- [ ] Add navigation between Nutrition and Workout sections using React Navigation

### 🔹 Phase 5 – UI/UX Improvements & Final Testing

- [ ] Polish UI for better user experience (input forms, calendar, lists)
- [ ] Test edge cases and data handling (empty days, deleted meals, etc.)
- [ ] Refactor and clean up code before expanding to Workout module

> ✅ Once the nutrition module is complete and tested, a new roadmap will be created for the workout tracking section.

---

> Installation and configuration instructions will be added in the future, once the app reaches a more stable version.