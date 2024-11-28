## Raphael Adeyemo Portfolio Website

This project is a portfolio website for **Raphael Adeyemo**, a Creative Graphic & UI/UX Designer. The website showcases Raphael's profile, including personal information, contact details, and downloadable CV. It is designed to be simple yet visually appealing, leveraging modern web development technologies.

---

## Features

- **Responsive Design**: The site is mobile-friendly and adapts to different screen sizes.
- **Sidebar Profile**: Contains Raphael's picture, contact information, and links to social media profiles.
- **Downloadable CV**: Visitors can download Raphael's resume directly from the website.
- **Dynamic Messaging**: Displays custom status and messages passed via the URL parameters.
- **SweetAlert Integration**: Modern, visually appealing alerts for feedback messages.
- **Google Fonts Integration**: Uses the Poppins font for a clean, professional look.

---

## Project Structure

- **index.php**: Main entry point of the application.
- **contact.php**: Handles form submissions and sends email messages.
- **assets/**: Contains all static files, including:
  - **images/**: Profile picture, favicon, and other graphical assets.
  - **css/**: Styling files for the website.
  - **Adeyemo_Raphael_CV.pdf**: Raphael's downloadable CV.
- **Google Fonts & Icons**: Includes links to external resources like Google Fonts and Ionicons for icons.

---

## Setup Instructions

### Prerequisites
- A web server capable of running PHP (e.g., Apache or Nginx).
- Browser to view the website.

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Place the files in your web server's root directory.
3. Ensure the `assets/` directory is properly set up with the necessary files.
4. Start the server and access the website via your browser:
   ```
   http://localhost/index.php
   ```

### Passing Dynamic Messages
To display dynamic status and messages with SweetAlert:
- Append `status` and `message` parameters to the URL.
  Example:
  ```
  http://localhost/index.php?status=success&message=message_sent
  ```
- `status`: Can be `success` or `error` for feedback types.
- `message`: Use predefined message shortcodes (e.g., `message_sent`, `all_required`).

---

## Dependencies

- **PHP**: For server-side processing.
- **SweetAlert**: Provides modern, visually appealing alerts.
- **CSS**: Custom styling located in `assets/css/style.css`.
- **Ionicons**: Used for social media and contact icons.
- **Google Fonts**: Poppins font family.

---

## Customization

1. **Update Personal Information**:
   Modify the sidebar information, such as name, email, phone, and location, directly in `index.php`.

2. **Add/Update Social Links**:
   Update or add new social links in the `<ul class="social-list">` section.

3. **Change Styling**:
   Modify `assets/css/style.css` to adjust the visual appearance.

4. **SweetAlert Integration**:
   Customize alert types, titles, and buttons in the `Swal.fire()` method within `index.php`.

---

## License

This project is provided as-is for personal use and may not be redistributed or sold. Ensure proper credits to the designer if you adapt or use this project.

---

## Contact

For any inquiries or support:
- **Email**: [rooda43@gmail.com](mailto:rooda43@gmail.com)
- **LinkedIn**: [Raphael Adeyemo](https://www.linkedin.com/in/cyber1ord/)
- **GitHub**: [Cyber1ord](https://github.com/Cyber1ord)

---

This project is a showcase of Raphael Adeyemo's expertise in design and provides a professional platform to engage with clients or collaborators. The integration of SweetAlert ensures better user experience during interactions.