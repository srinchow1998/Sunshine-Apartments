# Sunshine-Apartments

🏢 Sunshine Apartments Web Application
Sunshine Apartments is a real-estate management web application designed to simplify the apartment leasing process. Built using ASP.NET Web API for the backend and Angular for the frontend, the application enables tenants to browse, filter, and rent apartments. The platform integrates Stripe for payment processing and leverages Azure services for key management and deployment, ensuring secure and efficient operations.

🔥 Key Features
Apartment Listings – View a list of available apartments with advanced filtering options for bedrooms, bathrooms, price, and more.

Apartment Details – Comprehensive details for each apartment, including images, amenities, price, and availability.

Payment Integration with Stripe – Secure payment handling through Stripe, enabling tenants to pay rent and view payment history.

Email Webhooks for Payment Notifications – Stripe webhooks trigger email notifications to both tenants and admins when payments are processed, including successful payments and failed transactions.

Digital Lease Agreement Signing – Tenants can sign lease agreements electronically, eliminating the need for paper contracts.

Email Webhooks for Lease Contract Notifications – Webhooks trigger email notifications when lease agreements are signed, renewed, or about to expire, keeping both tenants and administrators informed.

Admin Dashboard – Admin users can manage apartment listings, approve/decline lease applications, track payments, and manage tenant records.

User Authentication and Authorization – Secure login with JWT authentication to ensure proper access levels for tenants and admins.

🛠 Tech Stack
Frontend: Angular (Responsive and dynamic UI for enhanced user experience)

Backend: ASP.NET Web API (RESTful API architecture)

Database: SQL Server (used for storing tenant details, apartment info, and payment records)

Payment Gateway: Stripe (for secure online payments)

Email Notifications: Email webhooks (for payment and lease contract updates)

Authentication: JWT (JSON Web Tokens for secure and scalable user management)

Cloud Services: Azure (for managing keys, secrets, and deployments)

Hosting/Deployment: Azure App Service and Azure Storage (for reliable deployment and storage solutions)

💡 Additional Features
Payment History – Tenants can track their past payments, view receipts, and manage upcoming rent dues.

Lease Renewal Notifications – Automated email reminders for lease renewal, ensuring tenants and admins stay on top of lease dates.

Admin Alerts – Admins receive notifications about payment status and contract updates, enabling quick action and seamless management.
