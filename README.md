# Responsive Sidebar with HTML, CSS, and JavaScript

This repository contains a project for creating a responsive sidebar navigation using HTML, CSS, and JavaScript. The sidebar features expandable menus, smooth animations, and an elegant design tailored for modern web applications.

## Features

- **Responsive Design**: The sidebar adjusts seamlessly for different screen sizes.
- **Expandable Menus**: Dropdown menus for nested navigation items.
- **Custom Scrollbar**: Styled scrollbar for better aesthetics.
- **Modern Aesthetic**: Clean and minimalistic UI built with custom CSS variables.
- **Smooth Animations**: Subtle transitions for enhanced user experience.

## Technologies Used

- **HTML**: For structuring the layout.
- **CSS**: For styling and animations.
- **JavaScript**: For interactivity and dynamic behavior.

## Project Structure

```
.
├── icons                            # Icons used in the project
│   ├── calendar_month_24dp_E8EAED_FILL0_wght400_GRAD0_opsz24.svg
│   ├── checklist_24dp_E8EAED_FILL0_wght400_GRAD0_opsz24.svg
│   ├── create_new_folder_24dp_E8EAED_FILL0_wght400_GRAD0_opsz24.svg
│   ├── dashboard_24dp_E8EAED_FILL0_wght400_GRAD0_opsz24.svg
│   ├── home_24dp_E8EAED_FILL0_wght400_GRAD0_opsz24.svg
│   ├── keyboard_arrow_down_24dp_E8EAED_FILL0_wght400_GRAD0_opsz24.svg
│   ├── keyboard_double_arrow_left_24dp_E8EAED_FILL0_wght400_GRAD0_opsz24.svg
│   └── person_24dp_E8EAED_FILL0_wght400_GRAD0_opsz24.svg
├── index.html                       # Main HTML file
├── dashboard.html                   # Dashboard HTML file
├── calendar.html                    # Calendar HTML file
├── profile.html                     # Profile HTML file
├── style.css                        # Stylesheet for the project
└── app.js                           # JavaScript logic
```

## Setup and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/IlyasBlidi/<repository-name>.git
   ```

2. Navigate to the project directory:
   ```bash
   cd sidebar-menu
   ```

3. Open `index.html` in your browser to view the project.

## How It Works

### HTML
- The main structure includes a `<nav>` element for the sidebar and a `<main>` element for the content.
- List items (`<li>`) are used for navigation links and expandable menus.

### CSS
- A dark theme with custom CSS variables for consistent styling.
- Smooth transitions and animations for opening/closing menus.
- Custom scrollbar styling for improved aesthetics.

### JavaScript
- Handles the sidebar toggle functionality using the `toggleSidebar` function.
- Controls dropdown menus with the `toggleSubMenu` function.

---

Enjoy the responsive sidebar! 🎉
