📖 More About This Project
This Movie Ticket Booking Website is a scalable full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js), designed to replicate a real-world movie booking experience. It offers a secure, user-friendly, and responsive platform for users and administrators alike.

🧠 Key Highlights
🎫 Real-Time Seat Booking:
Users can select movie shows and reserve seats with real-time UI updates. Booked seats are instantly locked and reflected across user sessions.

🔐 Authentication with Clerk:
Fully integrated Clerk authentication for:

Email, phone, and social logins

Multi-session support

Seamless account switching

Secure route protection for user and admin roles

📬 Background Jobs via Inngest:
Used Inngest to handle non-blocking, time-based, and event-driven tasks such as:

Email notifications for booking confirmations and show reminders

New movie alert emails to users

Seat timeout logic (for failed/canceled transactions)

⏳ Seat Locking Mechanism:
Implemented a timeout system that temporarily locks selected seats for 10 minutes during payment. If payment fails or is canceled, the seats are freed after timeout using scheduled jobs (via Inngest).

🛠️ Admin Dashboard:
Role-based access for admins to:

Add/Edit/Delete movies

Manage shows

View bookings and users

Monitor platform activity

📱 Fully Responsive UI:
Built using React and TailwindCSS, ensuring a smooth user experience across devices (mobile, tablet, desktop).

🌐 Deployment:
Application is deployed with production-ready optimizations, and supports environment-based configurations for scaling.
