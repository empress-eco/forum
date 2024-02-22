<div align="center">
  <img src="https://user-images.githubusercontent.com/9355208/190904451-ac6f171b-26c6-4432-a04f-044974516da6.png" alt="Empress Forum logo" height="50">
  <p align="center">A user-centric, open-source communication solution for remote teams.</p>
</div>

<div align="center">
  <a href="https://dashboard.cypress.io/projects/y2q697/runs">
    <img alt="cypress" src="https://img.shields.io/endpoint?url=https://dashboard.cypress.io/badge/simple/y2q697/main&style=flat&logo=cypress">
  </a>
  <a href="https://github.com/empress-eco/forum/blob/main/LICENSE">
    <img alt="license" src="https://img.shields.io/badge/license-MIT-blue">
  </a>
</div>

## About Empress Forum

Empress Forum, formerly Gameplan, is an interactive tool designed specifically for remote teams who prefer asynchronous discussions. It organizes and archives your team's knowledge and discussions around projects, delivering meaningful and trackable conversations that reduce chaos and increase productivity.

#### Key Features
- Organize discussions into projects as part of a team.
- Surface important information for your project and team in the Readme.
- User-friendly layout that optimizes discussion readability.
- Customize your Team and Project with emojis.
- People directory with individual profile pages.
- Set cover image, profile photo, short bio, and an 'About me' section.
- Powerful search capabilities to find older discussions.
- A common discussions feed showing discussions from across projects and teams.
- Delightful user experience.

## Technical Stack and Setup Instructions

#### Backend
Empress Forum is built on [Framework](https://Empressframework.com), a batteries-included python web-framework. The key technologies used include:

- [Python](https://www.python.org)
- [Redis](https://redis.io/)
- [MariaDB](https://mariadb.org/)
- [Socket.io](https://socket.io/)

#### Frontend
The frontend of Empress Forum is a VueJS SPA which uses a component library called [Empress UI](https://github.com/Empress/Empress-ui). It includes the following technologies:

- [VueJS](https://vuejs.org)
- [Empress UI](https://github.com/Empress/Empress-ui)
- [TailwindCSS](https://tailwindcss.com)
- [HeadlessUI](https://headlessui.com)

### Installation Instructions
Before you start, ensure you have Docker, docker-compose, and git set up on your machine. You can refer to the [Docker documentation](https://docs.docker.com/) for setup instructions.

To get a development environment running, follow these steps:

```sh
git clone https://github.com/empress-eco/forum.git
cd forum/docker
docker-compose up
```
Once the setup script creates a site, access `http://localhost:8000` in your browser. The Empress Forum login screen should appear. Log in using the following credentials:

- Username: `alex@example.com`
- Password: `123`

## Usage

After logging in, you can start creating teams and projects to organize discussions. You can customize each project and team with unique emojis, cover images, and more. Use the search tool to find older discussions and archive important information in the Readme section. 

## Contribution Guidelines
We welcome contributions from the community. If you have an idea that could improve Empress Forum, join our [Discussions](https://github.com/empress-eco/forum/discussions). If you find any bugs, please report them [here](https://github.com/empress-eco/forum/issues).

## License and Acknowledgements

### License
This project is licensed under the MIT License.

### Acknowledgements
We extend our profound gratitude to the Empress Community, whose pioneering work on the Framework has been instrumental in building Empress Forum. We appreciate their innovation, dedication, and ongoing support.