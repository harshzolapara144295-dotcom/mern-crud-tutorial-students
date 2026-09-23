# Student Management CRUD Application

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-18.x-brightgreen.svg)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-18.x-61dafb.svg)](https://react.dev/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

An open-source full-stack CRUD application engineered for managing student academic records. Built with a Node.js/Express REST API backend, MySQL database integration, and an interactive React single-page frontend.

---

## Architecture Overview

```text
[ React Frontend (Client) ] 
            | (HTTP / JSON via Axios or Fetch)
            v
[ Express.js REST API (Port 8081) ]
            | (SQL Queries)
            v
[ MySQL Database (Student Records) ]
