### **SafeComm_Transportation**

**Storyline:**  
SafeComm is a community-based safety app aimed at improving public transportation by tracking real-time locations of public transit vehicles and providing safety ratings for routes and areas. The app helps users make informed decisions about their daily commutes based on real-time data and community feedback.

---

### **Project Goal:**

The goal is to build a backend system that manages real-time tracking of public transportation, user interactions for safety ratings, and data storage for transit and user safety reports.

---

### **Minimum Expected Features:**

1. **User Authentication:**

   - JWT-based user registration and login system to authenticate users securely.

2. **Transit Tracking API:**

   - API to track public transportation vehicles in real time. This data will be sourced from third-party services, such as Google Maps, and shown to users in the app.

3. **Role-Based Access Control (RBAC):**

   - Implement RBAC to control different levels of access. Regular users can rate routes and view transit information, while admins can manage transit data and monitor reports.

4. **Third-Party Location Integration:**

   - Integrate a third-party location API (e.g., Google Maps) to track public transit vehicles and provide users with live updates on their locations.

5. **Route Safety Rating Service:**

   - Users can rate the safety of public transit routes based on personal experiences, enabling others to make informed decisions when choosing their route.

6. **MongoDB Integration:**

   - Use MongoDB to store essential data such as user profiles, transit data, route ratings, and user-reported safety issues.

7. **API Testing:**
   - Implement unit and integration tests for all APIs using Mocha or Jest to ensure that the backend functions as expected under various conditions.

---

### **Unique Feature:**

1. **Initial Route Safety Consultation:**
   - When users select a route for the first time, the system will show them similar routes that have been previously rated in terms of safety. It uses an algorithm to analyze routes and present the most relevant safety ratings from other users, allowing them to make safer travel choices.

---

### **Challenging Features:**

1. **Complex Data Visualization:**

   - Provide complex data visualizations for admins to monitor and analyze the safety ratings of different routes and areas over time. Data like the number of safety incidents and route ratings will be displayed via charts and graphs.

2. **Unsafe Situation Reporting API:**

   - Allow users to report unsafe situations in real-time, whether it be on a specific route or in transit vehicles. This data will be visible to other users and stored in the database for administrators to review.

3. **Estimated Wait Times for Public Transit:**
   - Provide users with estimated wait times for buses and trams based on live transit data, helping them plan their commutes more efficiently.

---
