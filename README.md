# **Currency Converter App with React Hooks and API Integration**

This project is a **Currency Converter** built using React, demonstrating modern React concepts such as **hooks**, **state management**, and real-time data fetching via **API calls**. It provides users the ability to convert one currency to another dynamically, using live exchange rates from an external API, ensuring no hardcoded values.

#### **Features:**
1. **Dynamic Currency Conversion:** 
   - Allows users to select from a list of available currencies and input the amount to convert. The app then fetches real-time conversion rates using a currency exchange API.
   
2. **React Hooks for State Management:**
   - **`useState`** is used for managing the selected currencies and input values (amounts).
   - **`useEffect`** handles the API calls to fetch exchange rates when currency or amount changes.

3. **API Integration (Real-Time Exchange Rates):**
   - Currency exchange rates are fetched from a live API (like **ExchangeRate-API** or **Open Exchange Rates**).
   - The API call is triggered when the user changes either the currency or the amount to convert, ensuring up-to-date conversion rates.

4. **No Hardcoded Values:**
   - Currency options and exchange rates are **dynamically fetched** from the API. This avoids hardcoding currency lists or rates.
   - The app will work globally and supports multiple currencies, which are pulled from the API response.

5. **Responsive UI:**
   - The app is designed to be responsive and user-friendly across devices. A simple, clean interface ensures easy usability, with dropdowns for currency selection and input fields for the amount.

#### **Technologies Used:**
- **React**: To build the user interface.
- **React Hooks** (`useState`, `useEffect`): For managing component state and side effects.
- **API Calls**: Using `fetch()` or `axios` to retrieve live currency data from a third-party API.
- **CSS/SCSS**: For styling and ensuring the application is responsive.

---

### **How It Works:**
1. **Currency Selection**: Users choose both the "from" and "to" currencies from dynamically populated dropdowns based on the API.
2. **Input Amount**: Users enter the amount they want to convert.
3. **Live Conversion**: The app fetches the latest exchange rates via API calls and converts the amount instantly.
4. **Display**: The converted amount is displayed, with an option to swap the currency selections.

---

### **Potential Extensions:**
- Add a feature to **swap** currencies.
- Show historical data and trends using chart libraries like **Chart.js**.
- Implement **local storage** to remember the user's preferred currencies.

This project demonstrates how React hooks and state management are used efficiently, ensuring scalability and dynamic data handling without hardcoded values.
