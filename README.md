<div align="center">
    <h1 style="font-family: Arial;">
        Backend code for BugTrackr
    </h1>

[![Website shields.io](https://img.shields.io/badge/version-v1-blue?style=for-the-badge)]()
[![License: MIT](https://img.shields.io/badge/LICENSE-MIT-blue?style=for-the-badge&color=orange)]()

</div>

<details open="open">
    <summary>Table of Content</summary>
    <ol>
        <li>
            <a href="#about">What is this?</a>
        </li>
        <li><a href="#getting-started">Getting started</a></li>
            <ul>
                <li><a href="#requirements">Requirements</a></li>
                <li><a href="#install">Installation</a></li>
            </ul>
        <li><a href="#license">License</a></li>
    </ol>
</details>
<h1 id="about">What is this?</h1>

BugTracker-backend is the backend code written for our mini-project of semester 6. It is written in NodeJS and uses ExpressJS as the framework. It uses MongoDB as the database and Mongoose as the ODM. JWT is used for authentication and authorization. Being REST APIs, it can be used with any frontend framework of your choice.

<h1 id="getting-started">Getting Started</h1>

This section will cover what you need to setup BugTrackr-backend locally.

<h2 id="requirements">Requirements</h2>

- Yarn (or npm)
- Postman (or any other API testing tool)
- MongoDB (or MongoDB Atlas)

<h2 id="install">Setting up locally</h2>

Create a mongoDB database and add the connection string to the default.json file in the config directory.

> _The connection string would look something like this := if you get an error with wails, run wails doctor._

```json
{
  "db": "mongodb+srv://<username>:<password>@cluster0.w2efo32.mongodb.net/?retryWrites=true&w=majority"
}
```

Clone the Repository:

```bash
git clone https://github.com/Athul0491/BugTrackr-backend.git
```

Navigate to the Project Directory:

```bash
cd BugTrackr-backend
```

Run BugTrackr-backend in dev mode:

```bash
yarn start
```

This will run the backend on port 5000. You can change this in the index.js file.

<h1 id="license">License</h1>

This project is licensed under the MIT License, making it open and accessible for everyone.
