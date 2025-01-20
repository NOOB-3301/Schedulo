<p align="center">
    <img src="https://github.com/user-attachments/assets/777dcdf6-c510-4d44-909f-f94d7056b33f" align="center" width="30%">
</p>
<p align="center"><h1 align="center">SCHEDULO</h1></p>
<p align="center">
	<em>Time, streamlined. Events, organized. Effortlessly.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/mukundsolanki/Schedulo?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/mukundsolanki/Schedulo?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/mukundsolanki/Schedulo?style=default&color=0080ff" alt="repo-top-language">
</p>
<p align="center"><!-- default option, no dependency badges. -->
</p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<br>

## 🔗 Table of Contents

- [📍 Overview](#-overview)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
  - [☑️ Prerequisites](#-prerequisites)
  - [⚙️ Installation](#-installation)
- [🔰 Contributing](#-contributing)
- [🎗 License](#-license)

---

## 📍 Overview

A modern, intuitive event scheduling platform that streamlines the scheduling process and saves time by offering streamlined user signup, event creation, and registration processes. With sleek interfaces and dynamic functionalities, Schedulo ensures smooth user interactions. Perfect for organizations and businesses seeking efficient event scheduling solutions.

## Live at: [LINK](https://schedulo-eight.vercel.app/)

---

## 📁 Project Structure

```sh
└── Schedulo/
    ├── README
    ├── LICENSE
    ├── backend
    │   ├── .gitignore
    │   ├── package-lock.json
    │   ├── package.json
    │   └── src
    │       ├── index.js
    │       └── models
    └── schedulo-frontend
        ├── .gitignore
        ├── README.md
        ├── components.json
        ├── eslint.config.mjs
        ├── next.config.ts
        ├── package-lock.json
        ├── package.json
        ├── postcss.config.js
        ├── postcss.config.mjs
        ├── public
        │   ├── file.svg
        │   ├── globe.svg
        │   ├── next.svg
        │   ├── vercel.svg
        │   └── window.svg
        ├── src
        │   ├── app
        │   ├── components
        │   └── lib
        ├── tailwind.config.ts
        └── tsconfig.json
```


---
## 🚀 Getting Started

### ☑️ Prerequisites

Before getting started with Schedulo, ensure your runtime environment meets the following requirements:

- **Frontend env:**
    ```
        NEXT_PUBLIC_API_BASE_URL=http://localhost:5000
        NEXT_PUBLIC_EMAILJS_SERVICE_ID=emailjs_service_id
        NEXT_PUBLIC_EMAILJS_TEMPLATE_ID_ONLINE=emailjs_online_template_id
        NEXT_PUBLIC_EMAILJS_TEMPLATE_ID_OFFLINE=emailjs_offline_template_id
        NEXT_PUBLIC_EMAILJS_PUBLIC_KEY=emailjs_public_key
    ```

- **Backend env:**
    ```
        PORT=5000
        MONGO_URI=mongodb://localhost:27017
        JWT_SECRET=your_jwt_secret
    ```


### ⚙️ Installation

Install Schedulo locally using one of the following methods:

1. Clone the Schedulo repository:
```sh
❯ git clone https://github.com/mukundsolanki/Schedulo
```

2. Navigate to the project directory:
```sh
❯ cd Schedulo
```

3. Install dependencies for both frontend and backend:

**Using `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ cd schedulo-frontend && npm install
❯ cd backend && npm install
```

4. Start the application (frontend and backend simultaneously):

```sh
❯ cd schedulo-frontend && npm start
❯ cd backend && npm start
```


## 🔰 Contributing

- **💬 [Join the Discussions](https://github.com/mukundsolanki/Schedulo/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/mukundsolanki/Schedulo/issues)**: Submit bugs found or log feature requests for the `Schedulo` project.
- **💡 [Submit Pull Requests](https://github.com/mukundsolanki/Schedulo/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/mukundsolanki/Schedulo
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/mukundsolanki/Schedulo/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=mukundsolanki/Schedulo">
   </a>
</p>
</details>

---

### 🎗 License

This project is protected under the [MIT LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---