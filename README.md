# TradiHub

**Connecting Family Traditions Through Technology**

TradiHub is an open-source platform designed to connect individuals to their heritage, enabling the preservation and sharing of family traditions across generations.

## Table of Contents
1. [Overview](#overview)
2. [Repository Structure](#repository-structure)
3. [Live Demo](#live-demo)
4. [Technologies Used](#technologies-used)
5. [UML Diagrams](#uml-diagrams)
6. [Getting Started](#getting-started)
    - [Frontend Setup](#frontend-setup)
    - [Backend Setup](#backend-setup)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

---

## Overview

TradiHub is a platform focused on bridging the gap between modern technology and ancient family traditions. It allows users to create and share family trees, preserve cultural heritage, and document family stories. Our mission is to provide a seamless digital experience for people wishing to preserve their unique history.

---

## Repository Structure

The repository uses a **monorepo** approach, containing both the frontend (React) and backend (Spring Boot) codebases.


Each subdirectory (`/frontend` and `/backend`) contains its own `README.md` with instructions specific to that part of the project.

---

## Live Demo

Check out a live demo of TradiHub [not yet available](https://example.com).

---

## Technologies Used

- **Frontend**: React, JavaScript, CSS, HTML
- **Backend**: Spring Boot, Java, MySQL
- **Other Tools**: Docker, GitHub Actions, Maven
- **Documentation**: UML diagrams (use case, class, sequence)

---

## UML Diagrams

To help developers understand the architecture and structure of the project, we provide the following UML diagrams:

### Use Case Diagram
The use case diagram illustrates the main interactions between users and the system.
![Use Case Diagram](uml/usecase-diagram.png)

### Class Diagram
The class diagram shows the structure of the backend, detailing relationships between entities.
![Class Diagram](uml/class-diagram.png)

### Sequence Diagram
The sequence diagram illustrates the interaction flow between the frontend and backend.
![Sequence Diagram](uml/sequence-diagram.png)

---

## Getting Started

### Prerequisites
- Node.js and npm (for frontend)
- Java 17 or later (for backend)
- Docker (optional for containerized deployment)

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
2. Install the dependencies:
   ```bash
   npm install
3. Run the application:
   ```bash
   npm start
For detailed frontend setup instructions, check the [frontend README](frontend/README.md).
### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend

3. Build the Spring Boot application:
   ```bash
   ./mvnw clean install

5. Run the application:
   ```bash
   ./mvnw spring-boot:run

For detailed backend setup instructions, check the [backend README](backend/README.md).

---

## Contributing
We welcome contributions! Please check out our [CONTRIBUTING.md](docs/CONTRIBUTING.md) for guidelines on how to get involved.

Some ways you can contribute:
- Submit bug reports and feature requests through [GitHub Issues]()
- Review and submit Pull Requests (PRs)
- Add or improve UML diagrams, documentation, or project features

## Code of Conduct
Please read our [Code of Conduct](docs/CODE_OF_CONDUCT.md) to ensure a welcoming and respectful environment.

---

## License 
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

## Contact
If you have any questions or feedback, feel free to contact us via frankpythagore@gmail.com | .


---

## Acknowledgments
### Project Founders
- [Youaleu Tchouassi Frank Loic](https://pythagore.vercel.app/) - Lead developer
- [Vanya Toumi Bertomy]() - Backend developer
- [Pelayah Epoupa](https://github.com/Peliah) - Frontend developer
- [Selapoue Noua Aimerick]() - Full stack developer
- [Tchuente Yado Yvan]() - UI/UX and Full stack developer


---

### Markdown File Locations:

1. **Frontend README** (`/frontend/README.md`)
   - Instructions for setting up and running the React frontend.

2. **Backend README** (`/backend/README.md`)
   - Instructions for setting up and running the Spring Boot backend.

3. **Contributing Guidelines** (`docs/CONTRIBUTING.md`)
   - How to contribute to the project.

4. **Code of Conduct** (`docs/CODE_OF_CONDUCT.md`)
   - Behavioral guidelines for contributors.

5. **License** (`LICENSE.md`)
   - License details (MIT in this case).

6. **UML Diagrams** (`/uml/`)
   - Folder containing UML diagrams.

7. **Assets Folder** (`/assets/`)
   - Contains images like logos, architecture diagrams, or design files (e.g., Figma).

---

This markdown structure will be clear for contributors and users, guiding them through setup, contribution, and navigation within the repository.
