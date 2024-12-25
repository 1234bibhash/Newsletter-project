---

# Email Newsletter Application

A powerful and user-friendly email newsletter application that allows users to design, save, and send professional emails effortlessly. Built with React, Next.js, and Resend API, this application is perfect for managing email campaigns effectively.

---

![News-letter](Newletter-image)


## Features

### Email Creation and Management
- Drag-and-drop email editor for designing professional email templates.
- Save drafts to revisit and edit later.
- Real-time email preview to ensure perfect formatting.

### Email Delivery
- Secure and efficient integration with **Resend API** for email delivery.
- Reliable sending to multiple recipients.
- Error handling for failed email delivery attempts.

### User-Friendly Interface
- Intuitive and responsive design.
- Minimalist UI for seamless navigation.

---

## Technologies Used

- **React**: Frontend library for building a responsive and dynamic UI.
- **Next.js**: Framework for server-side rendering and API integration.
- **TypeScript**: For type safety and enhanced development experience.
- **TailwindCSS**: For styling and layout.
- **Resend API**: To handle email delivery.
- **Axios**: For API requests.
- **Nodemailer**: Alternative email-sending library for debugging.
- **Clerk**: For user authentication and session management.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/email-newsletter-app.git
   cd email-newsletter-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the project root and add the following:
   ```env
   RESEND_API_KEY=your_resend_api_key
   NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_frontend_api
   CLERK_API_KEY=your_clerk_api_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open the app in your browser at `http://localhost:3000`.

---

## Usage

1. Navigate to the email editor page.
2. Design your email using the drag-and-drop editor.
3. Save the draft or send the email directly to your recipients.
4. Monitor email delivery status in the logs.

---

## Project Structure

```
src/
├── app/                 # Application-specific routes and logic
├── shared/              # Reusable utilities and components
│   ├── components/      # UI components
│   ├── utils/           # Helper functions like email sender
│   ├── assets/          # Static assets like default templates
├── styles/              # Global and TailwindCSS styles
├── pages/               # Next.js pages and routing
```

---

## API Integration

### Resend API
The application integrates with Resend for sending emails. 
- API documentation: [https://resend.com/docs](https://resend.com/docs)

### Clerk Authentication
User authentication and session handling is managed using Clerk. 
- API documentation: [https://clerk.dev/docs](https://clerk.dev/docs)

---

## Contribution

Contributions are welcome! To contribute:
1. Fork this repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- **React Email Editor** for the drag-and-drop editor.
- **Resend API** for seamless email delivery.
- **Clerk** for simplifying authentication.

--- 

Start building your email campaigns with the **Email Newsletter Application** today! 🚀

