
> **Note**: This is a single-file application for simplicity and easy deployment.

---

## 🧑‍⚕️ How to Use

### Step 1: Onboarding (First Time)
1.  Enter your **name** and **age** (age helps customize health tips).
2.  Select what you want to be reminded about (Medication, Checkup, Hydration, Exercise, or Custom).
3.  Type the reminder details (e.g., "Take blood pressure pill").
4.  Click **"Set Reminder & Continue"**.

### Step 2: Confirmation Page
-   You will see a confirmation message with your reminder details.
-   Click **"Go to my Dashboard"** to enter the main app.

### Step 3: Dashboard
-   **View reminders** – All your reminders are listed with time and category.
-   **Add new reminders** – Use the form at the bottom of the left panel.
-   **Mark as complete** – Click the ✓ button on any reminder.
-   **Delete reminders** – Click the 🗑 button to remove a reminder.
-   **Track progress** – The metrics panel shows total, pending, and completed counts.
-   **Get wellness tips** – The right panel shows rotating health advice.

---

## 🎨 Customization

You can easily adapt this project:

-   **Change the dark theme colors**: Modify the CSS variables in the `body`, `.header`, and `.card` classes.
-   **Add more reminder types**: Update the `<select>` options in the dashboard and onboarding.
-   **Add more health tips**: Extend the `tips` array in the JavaScript `rotateWellnessTip()` function.
-   **Adjust age-based reminders**: Modify the logic in `handleOnboardingConfirm()` that adds extra reminders for users over 60.

---

## 🔒 Privacy

All data is stored **exclusively on your local machine** using the browser's `localStorage`. No information is sent to any server or third party. Your name, age, and health reminders never leave your device.

---

## 🌍 Localization

The interface includes a bilingual touch (English & Tigrinya) in the header to honor the cultural context of Tigray. You can easily expand this for full localization.

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for improving the app or adding new features (like sound notifications, reminder scheduling with alerts, or data export), feel free to:

1.  Fork the repository.
2.  Create a feature branch.
3.  Submit a pull request.

---

## 📄 License

This project is open-source and available under the **MIT License**. You are free to use, modify, and distribute it as you wish.

---

## 💬 Acknowledgements

-   Inspired by the need for simple, accessible, and culturally-aware health tools.
-   Dark theme designed for comfortable extended use.
-   Icons and emojis used for better visual communication.
-   Special thanks to the open-source community.

---

## 📧 Contact

For questions or suggestions, please open an issue on the GitHub repository page.

---

*Stay healthy, stay consistent — ጥዕና ይሃብኩም* 💙🌾
