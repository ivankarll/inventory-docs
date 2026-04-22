# Installation Guide

This guide covers the basic steps to get the inventory system running in your local development environment.

## Prerequisites

Before starting, ensure you have the following installed:

* **PHP**: (e.g., 8.2+)
* **Composer**: For PHP dependency management.
* **Node.js & npm**: For compiling frontend assets.
* **MySQL**: Or an equivalent SQL database server.
---
## Quick Setup

Choose the tab below that matches your operating system:

=== "Bash (Linux / macOS / WSL)"
    1. **Install PHP dependencies**
       ```bash
       composer install
       ```
    2. **Install JS dependencies**
       ```bash
       npm install
       ```
    3. **Initialize environment file**
       ```bash
       cp .env.example .env
       ```

=== "PowerShell (Windows)"
    1. **Install PHP dependencies**
       ```powershell
       composer install
       ```
    2. **Install JS dependencies**
       ```powershell
       npm install
       ```
    3. **Initialize environment file**
       ```powershell
       Copy-Item .env.example .env
       ```



