# CICD-assignment

This repository is a sample Python project designed to demonstrate the implementation of Continuous Integration and Continuous Delivery (CI/CD) pipelines. It is intended as an assignment for exploring automated testing, build processes, and deployment strategies.


## Project Structure

- **.**: Contains the Flask API backend.
- **.github/workflows/**: GitHub Actions configuration files for CI/CD.
- **docker-compose.yml**: Orchestrates the dockerfile

## Getting Started

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/)

### Installation

Clone the repository and change into the project directory:

```bash
git clone https://github.com/hpcclab/CICD-assignment
cd CICD-assignment
```
## Running the Application

Build and start the services with Docker Compose:

(simple)

```bash
python .\app.py
```

Using Docker - 

```bash
docker-compose up --build
```

### By Default

- The **React frontend** will be available at [http://localhost:3000](http://localhost:3000)
- The **Flask backend API** will run at [http://localhost:5000](http://localhost:5000)

### CI/CD

This repository is set up with GitHub Actions to automatically run tests and build Docker images on commits and pull requests. The CI/CD configuration can be found in the `.github/workflows` directory.
T r i g g e r i n g   C I / C D  
 T r i g g e r i n g   C I / C D  
 T r i g g e r   p i p e l i n e  
 F i n a l   d e p l o y m e n t   t e s t  
 t e s t   d e p l o y   f i x  
 t r i g g e r   l o g i n   f i x  
 u s i n g   e n v i r o n m e n t   s e c r e t s  
 t e s t   e n v i r o n m e n t   s e c r e t s   f i x  
 c l e a n e d   u p   d u p l i c a t e   Y A M L   f i l e  
 