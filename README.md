
# Hotel Booking Client

This is the frontend client for the Hotel Booking application, built with React and Vite.

## Features
- Browse and book hotel rooms
- View exclusive offers and featured destinations
- User authentication with Clerk
- Responsive and modern UI

## Getting Started

### Prerequisites
- Node.js (v16 or higher recommended)
- npm or yarn

### Installation
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd Hotel-booking/client
   ```
2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root of the `client` folder.
   - Add your Clerk publishable key:
     ```env
     VITE_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key-here
     ```

### Running the App
Start the development server:
```sh
npm run dev
# or
yarn dev
```

The app will be available at `http://localhost:5173` by default.

## Project Structure
- `src/` - Main source code
  - `components/` - Reusable UI components
  - `pages/` - Application pages
  - `assets/` - Images and icons
- `public/` - Static files
- `.env` - Environment variables

## License
This project is licensed under the MIT License.
