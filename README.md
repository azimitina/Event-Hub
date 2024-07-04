# Event Hub

Your event organization web app - post an event, set a price, and get paid via Stripe.

Built on Next.js 14, Event Hub is a comprehensive, full-stack platform for managing events. It serves as a central hub, showcasing diverse events from around the world. With seamless Stripe payment processing, you can purchase tickets for any event or create and manage your own events effortlessly.

## Tech Stack

- Node.js
- Next.js
- TypeScript
- Tailwind CSS
- Stripe
- Zod
- React Hook Form
- Shadcn
- uploadthing

## <a name="features">✨ Features</a>

🚀 **Authentication (CRUD) with Clerk:** Secure and efficient user management through Clerk, ensuring seamless authentication.

🚀 **Events (CRUD):** Comprehensive functionality for creating, reading, updating, and deleting events, giving users full control over event management.

- **Create Events:** Easily generate new events with essential details such as title, date, location, and additional information.
- **Read Events:** Access a detailed view of all events, exploring specifics including descriptions, schedules, and related information.
- **Update Events:** Dynamically modify event details to ensure information remains accurate and up-to-date.
- **Delete Events:** Remove events from the system effortlessly, allowing administrators to manage and curate the platform effectively.

🚀 **Related Events:** Smartly connects and displays related events on the event details page, making it more engaging for users.

🚀 **Organized Events:** Efficiently organizes events, ensuring a structured and user-friendly display, such as showing events created by the user on their profile.

🚀 **Search & Filter:** Robust search and filter system enabling users to easily find events that match their preferences.

🚀 **New Category:** Dynamic categorization allows seamless addition of new event categories, keeping the platform adaptable.

🚀 **Checkout and Pay with Stripe:** Smooth and secure payment transactions using Stripe, enhancing the user experience during the checkout process.

🚀 **Event Orders:** Comprehensive order management system providing a clear overview of all event-related transactions.

🚀 **Search Orders:** Quick and efficient search functionality for orders, facilitating easy tracking and management.

And many more features, including code architecture and reusability, to enhance your experience.

## <a name="quick-start"> Quick Start</a>

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#NEXT
NEXT_PUBLIC_SERVER_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_CLERK_WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#MONGODB
MONGODB_URI=

#UPLOADTHING
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Replace the placeholder values with your actual credentials

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
