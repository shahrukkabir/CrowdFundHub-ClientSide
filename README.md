# Crowdcube - Client Side

Crowdcube is a modern and user-friendly crowdfunding platform that enables users to create and manage fundraising campaigns. It allows contributors to support various causes, startups, and creative ideas by making donations.

## Live Site
[Visit Crowdcube](#https://crowd-funding-b2152.web.app/)

## Key Features

- **Responsive Design**: Fully optimized for mobile, tablet, and desktop.
- **User Authentication**: Firebase-based login with email/password and Google authentication.
- **Campaign Management**:
  - Users can create, view, and manage their campaigns.
  - Campaigns display essential details with donation options.
- **Protected Routes**: Add Campaign, My Campaigns, and My Donations are accessible only to logged-in users.
- **Dark/Light Mode**: Switch between themes for a better user experience.
- **Notifications**: Toast messages for successful actions like login, campaign creation, and donations.

## Technologies Used

- **Frontend**: React.js, React Router, Context API, Axios
- **State Management**: React Context API
- **Authentication**: Firebase Authentication
- **UI Components**: React Bootstrap, CSS, Lottie React
- **Database**: Firebase, MongoDB (for storing campaigns and donations)

## Setup Instructions

### Prerequisites
- Node.js (v14 or later)
- NPM or Yarn
- Firebase Project (for authentication and storage)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-repo/crowdcube-client
   ```
2. **Navigate to the project directory:**
   ```sh
   cd crowdcube-client
   ```
3. **Install dependencies:**
   ```sh
   npm install
   ```
4. **Create a `.env` file** and add Firebase configuration:
   ```env
   REACT_APP_FIREBASE_API_KEY=your-api-key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
   REACT_APP_FIREBASE_PROJECT_ID=your-project-id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-sender-id
   REACT_APP_FIREBASE_APP_ID=your-app-id
   ```
5. **Run the app:**
   ```sh
   npm start
   ```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License
Distributed under the MIT License.

