# Daily Tasks Note & Dashboard

A modern, web-based daily task note and dashboard application for teams, powered by Google Apps Script backend. This project allows users to record daily notes, track blockers, and view analytics and user management in a beautiful, responsive interface.

## Features

- **Daily Task Note Submission**: Users can submit their daily notes, including yesterday's accomplishments, today's focus, blockers, and context notes.
- **User Dropdown**: Dynamically loads user list from backend for easy selection.
- **Dashboard**: Secure login-protected dashboard for analytics and user management.
- **Analytics**: Visualizes submissions per person and over time using Chart.js.
- **User Management**: Add or remove users from the dashboard.
- **Responsive UI**: Built with Tailwind CSS for a clean, modern look on all devices.

## How It Works

- The frontend is a single HTML file (`index.html`) using Tailwind CSS, Chart.js, and Font Awesome.
- All data (users, notes, authentication) is managed via a Google Apps Script web app (see `SCRIPT_URL` in the code).
- Users submit notes, which are sent to the backend and stored (typically in a Google Sheet).
- The dashboard provides analytics and user management, accessible after login.

## Usage Instructions

1. **Open the App**
   - Open `index.html` in your browser.

2. **Submit a Daily Note**
   - Fill in the date, select your name, and enter your daily notes.
   - Click "Record Note" to submit.

3. **View Dashboard**
   - Click the "Dashboard" tab.
   - Log in with your credentials to access analytics and user management.

4. **Manage Users**
   - In the dashboard, switch to "User Management" to add or remove users.

## Customization

- **Backend Integration**: The app uses a Google Apps Script endpoint (see `SCRIPT_URL` in the JS). You can deploy your own script and update the URL as needed.
- **User List**: Managed via the backend; add/remove users from the dashboard.
- **Styling**: Modify Tailwind classes in `index.html` for custom styles.

## Technologies Used

- [Tailwind CSS](https://tailwindcss.com/) for UI styling
- [Chart.js](https://www.chartjs.org/) for data visualization
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Apps Script](https://developers.google.com/apps-script) for backend (not included in this repo)

## File Structure

```
dailytasksnote docs/
  ├── index.html   # Main application file
  └── README.md    # Project documentation (this file)
```

## Deployment

- Host the `index.html` file on any static web server (e.g., GitHub Pages, Netlify, Vercel, or your own server).
- Ensure your Google Apps Script backend is deployed and the `SCRIPT_URL` is updated accordingly.

---

## Support & Contact

For technical support or questions about this Petty Cash Manager system, please contact your system administrator or the development team.

**Version**: 1.0  
**Last Updated**: January 2024  
**Maintained By**: RBX Development Team 