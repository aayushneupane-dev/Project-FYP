# 🚗 FlexRide - Rent to Earn

FlexRide is a responsive single-page web platform that connects licensed drivers and riders with affordable rental vehicles for ride-sharing and delivery services.

---

## 📌 Overview

Many individuals have a valid driver's license but lack a vehicle to work on gig platforms like Pathao, InDrive, Uber, or Foodmandu. **FlexRide** solves this by providing an easy-to-use rental catalog featuring:

- **Work-based category filtering:** Easily find vehicles tailored for delivery or passenger rides.
- **Dynamic pricing:** Automatic rental cost calculations based on selected days.
- **Integrated checkout form:** Includes license verification and popular local payment options (**eSewa** and **Khalti**).

---

## ✨ Features

- **Responsive Header & Hero:** Clean navigation with a modern design layout across all devices.
- **Category Filtering:** Filter vehicles by *Food / Parcel Delivery*, *Ride-Sharing*, or *All Vehicles*.
- **Vehicle Catalog Cards:** Displays daily rental rates in NPR (`Rs.`), vehicle descriptions, and work tags.
- **Booking Modal:**
  - Automatically loads the chosen vehicle details.
  - Dynamically calculates the total price based on rental duration.
  - Includes input validation for full name, phone number, license number, and target platform.
  - Radio buttons to select payment via **eSewa** or **Khalti**.
- **Modern UI:** Built with glassmorphism, smooth animations, and clean hover states using pure CSS.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic structural markup and form controls.
- **CSS3:** Flexbox, CSS Grid, media queries, CSS variables, and keyframe animations.
- **JavaScript (ES6+):** Vanilla JavaScript for filtering, modal state management, and real-time price calculations.

---

## 📂 File Structure

```text
.
├── index.html       # Single file containing HTML, CSS styles, and JavaScript logic
└── README.md        # Project documentation
