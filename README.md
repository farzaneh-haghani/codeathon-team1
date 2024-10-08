# The Big Alliance Donation Website

## Project Description
The Big Alliance Donation Website helps users donate to various charity campaigns. It supports both individual and company donations, and administrators can manage campaigns and view reports. The site is designed for mobile and desktop, ensuring accessibility and security with multi-factor authentication and PayPal payments.

![image](https://github.com/user-attachments/assets/99943f25-ff0c-4799-88a1-9046a0159417)



## Technologies Used
- **Next.js**: For fast, responsive frontend.
- **TypeScript**: Ensures type safety and code reliability
- **Prisma**: For database management.
- **NextAuth**: For secure authentication.
- **PayPal**: To handle secure payments.

## Challenges and Future Plans
We worked to ensure user input validation and security (OWASP best practices). Future plans include adding more detailed reports and extending campaign features.

## How to Install and Run the Project
1. Clone the repository.
2. Run `yarn install` to install dependencies.
3. Create `.env` file with your environment variables (e.g., PayPal API keys, database connection).
4. Run `yarn run dev` to start the development server.

## How to Use the Project
- For admins: Log in to manage campaigns, view donations, and generate reports. Requires authentication (admin login with multi-factor authentication).
- For donors: Browse campaigns, donate via PayPal.
