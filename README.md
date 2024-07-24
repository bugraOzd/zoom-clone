# NextJS Zoom Clone

A feature-rich video conferencing application built with Next.js and TypeScript, replicating core functionalities of Zoom.

**Note**: This project is not written from scratch, but is developed by following a tutorial video. The original tutorial can be found at <a href='https://www.youtube.com/watch?v=R8CIO1DZ2b8'>here<a/>.

## Features

- **Authentication**: Secure login via Clerk, supporting social sign-on and email/password methods.
- **New Meeting**: Start meetings with configurable camera and microphone settings.
- **Meeting Controls**: 
  - Recording
  - Emoji reactions
  - Screen sharing
  - Mute/unmute
  - Sound adjustments
  - Grid layout
  - Participant list view
  - Individual participant management (pin, mute/unmute, block, allow video)
- **Exit Meeting**: Leave or end meetings for all participants.
- **Schedule Future Meetings**: Plan and manage upcoming meetings.
- **Past Meetings List**: Access details of previously held meetings.
- **View Recorded Meetings**: Review past meeting recordings.
- **Personal Room**: Unique meeting link for instant meetings.
- **Join via Link**: Easy access to meetings created by others.
- **Secure Real-time Functionality**: Ensures user privacy and data integrity.
- **Responsive Design**: Optimal user experience across various devices and screen sizes.

## Technologies Used

- **Next.js**: React framework for building server-side rendered and static web applications.
- **TypeScript**: Typed superset of JavaScript for enhanced developer experience and code quality.
- **Clerk**: Comprehensive user management and authentication solution.
- **GetStream**: Powerful APIs for building scalable activity feeds and chat messaging.
- **shadcn/ui**: A collection of re-usable components built using Radix UI and Tailwind CSS.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/your-username/nextjs-zoom-clone.git
   ```

2. Install dependencies:
   ```
   cd nextjs-zoom-clone
   npm install
   ```

3. Set up environment variables:
   Create a new file named `.env` in the root of your project and add the following content:

   ```
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=

   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

   NEXT_PUBLIC_STREAM_API_KEY=
   STREAM_SECRET_KEY=
   ```

   Replace the placeholder values with your actual Clerk & GetStream credentials. You can obtain these credentials by signing up on the Clerk website and GetStream website.

4. Run the development server:
   ```
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Acknowledgements

This project was created as a learning exercise, inspired by Zoom's functionality.

The implementation is based on the tutorial found at <a href='https://www.youtube.com/watch?v=R8CIO1DZ2b8'>JavaScript Mastery<a/>. Credit goes to the original content creator for the guidance and structure of this project.
