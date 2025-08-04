Absolutely! Here’s the full README content all in one chunk for easy copying:

````markdown
# User Directory

A simple Angular application to fetch and display a list of users from a public API.  
This project demonstrates basic Angular concepts including HttpClient API calls, services, routing, and error handling.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [API Details](#api-details)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

The User Directory app fetches user data from the public [JSONPlaceholder API](https://jsonplaceholder.typicode.com/users) and displays it in a user-friendly interface.  
This project is ideal for beginners looking to get hands-on experience with Angular’s HttpClient and routing capabilities.

---

## Features

- Fetch and display a list of users.
- View detailed information for individual users.
- Loading indicators while fetching data.
- Basic error handling for API failures.
- Clean component and service separation.
- Routing with parameterized routes.

---

## Technologies Used

- Angular 16+
- TypeScript
- RxJS
- SCSS (default styling)
- JSONPlaceholder API (for demo data)

---

## Getting Started

### Prerequisites

- Node.js (version 16+ recommended)  
  Download: [https://nodejs.org/](https://nodejs.org/)

- Angular CLI  
  Install globally (if not already installed):

```bash
npm install -g @angular/cli
````

---

### Installation

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/user-directory.git
cd user-directory
```

2. Install dependencies

```bash
npm install
```

---

### Running the Application

Start the development server:

```bash
ng serve
```

Open your browser and navigate to [http://localhost:4200](http://localhost:4200).
You should see the user list displayed.

---

## Project Structure

```
src/
├── app/
│   ├── components/
│   │   ├── user-list/
│   │   │   ├── user-list.component.ts
│   │   │   ├── user-list.component.html
│   │   │   └── user-list.component.scss
│   │   ├── user-detail/
│   │   │   ├── user-detail.component.ts
│   │   │   ├── user-detail.component.html
│   │   │   └── user-detail.component.scss
│   ├── models/
│   │   └── user.model.ts
│   ├── services/
│   │   └── user.service.ts
│   ├── app-routing.module.ts
│   ├── app.component.ts
│   └── app.module.ts
├── assets/
├── environments/
│   ├── environment.ts
│   └── environment.prod.ts
└── main.ts
```

---

## API Details

This project uses [JSONPlaceholder](https://jsonplaceholder.typicode.com/) — a free fake REST API for testing.

* **Get all users**: `GET https://jsonplaceholder.typicode.com/users`
* **Get user by ID**: `GET https://jsonplaceholder.typicode.com/users/{id}`

---

## Usage

* On loading the app, you will see a list of users.
* Click on a user’s name to navigate to their detailed info page.
* Use the back link on the detail page to return to the list.
* If the API call fails, a user-friendly error message is shown.
* Loading indicators appear while fetching data.

---

## Contributing

Contributions are welcome!
To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes and commit (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a Pull Request.

Please ensure code is clean and tested before submitting.

---

## License

This project is open-source and available under the MIT License.
See the [LICENSE](LICENSE) file for details.

---

*Happy coding! 🚀*

```
