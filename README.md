# Realtime-Calculator
API based Realtime Calculator

A simple web-based calculator that uses HTML, CSS, JavaScript, and the Math.js API to calculate the sum of two numbers in real time. The design is enhanced with clean and modern CSS for an elegant user experience.

---

## Tech Stack Used

### 1. **Frontend**:
- **HTML**: Structure of the web page.
- **CSS**: For styling the calculator.
- **JavaScript**: Handles user input and interacts with the API.

### 2. **Backend API**:
- **Math.js API**: Processes the addition of two numbers remotely and returns the result.

### 3. **Browser Features**:
- **Fetch API**: To make HTTP requests to the Math.js API.
- **Debouncing**: Reduces excessive API calls when users type continuously.

### 4.**Gettind Data from API and then show the sum**
- **When User finished adding the two it send call to api calculate in server and then show result in real-time**

---

## Future Improvements

### Features:
1. **Support for More Operations**:
   - Add subtraction, multiplication, and division.
   - Allow advanced mathematical operations like square roots, exponents, etc.

2. **Validation**:
   - Prevent API calls if inputs are empty or invalid.
   - Display detailed error messages for invalid inputs.

3. **History of Calculations**:
   - Store and display a history of recent calculations.
   - Allow users to clear the history.

4. **Responsive Design**:
   - Make the calculator fully responsive for mobile and tablet screens.

5. **Localization**:
   - Add support for multiple languages and number formats.

6. **Offline Mode**:
   - Use JavaScript for basic calculations when offline.

### Tech Upgrades:
1. **React or Vue.js**:
   - Build the UI with modern frameworks for better scalability.

2. **Backend Integration**:
   - Create a custom backend service instead of using Math.js API.
   - Use Node.js and Express for handling operations.

3. **Unit Testing**:
   - Add automated tests for all functionalities using Jest or Mocha.
