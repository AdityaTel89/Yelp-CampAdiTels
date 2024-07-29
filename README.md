# Yelp-CampAdiTels


# Campgrounds Web Application

This project is a dynamic web application for managing campgrounds. It allows users to create, edit, and remove campgrounds and reviews. Users can view all camps and reviews without signing up, but must log in to edit campground details or comments.

## Features

- **Campground **: Create, edit, and remove campgrounds.
- **User Authentication**: Login required for editing or deleting campgrounds and reviews.
- **Review System**: Users can add, edit, and remove reviews for campgrounds.
- **Public Access**: All users can view camps and reviews without needing to sign up.
- **Responsive Design**: Utilizes Bootstrap for a mobile-friendly interface.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: Passport.js

## Installation

### Prerequisites

- Node.js
- npm (Node Package Manager)
- MongoDB

### Clone the Repository

```bash
git clone https://github.com/yourusername/campgrounds-management.git
cd campgrounds-management
```

### Install Dependencies

```bash
npm install
```

### Set Up the Database

1. Make sure MongoDB is installed and running on your system.
2. Create a new database named `campgrounds`.
3. Configure your MongoDB URI in a `.env` file in the root directory:
   ```
   DATABASE_URL=mongodb://localhost:27017/campgrounds
   ```

### Environment Variables

Create a `.env` file in the root directory and set up the following variables:

```
DATABASE_URL=mongodb://localhost:27017/campgrounds
SECRET=your_secret_key
```

### Run the Application

```bash
node app.js
```

### Access the Web Application

Open your browser and go to `http://localhost:3000`.

## Usage

- **Campground **:
  - Create new campgrounds by clicking on "Add Campground".
  - Edit or delete your own campgrounds from the campground details page.
- **Review System**:
  - Add reviews to campgrounds from the campground details page.
  - Edit or delete your own reviews.
- **User Authentication**:
  - Sign up and log in to manage your campgrounds and reviews.
  - Public users can view all campgrounds and reviews.

## Contributing

We welcome contributions! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.
