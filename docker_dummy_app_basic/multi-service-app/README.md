# Multi-Service Application

## Overview

This multi-service application consists of three services:

1. **Web Service** (Spring Boot): Provides REST API to manage users.
2. **Database Service** (MySQL): Stores user data.
3. **Cache Service** (Redis): Caches user data for quick retrieval.

## Requirements

- Docker 20.10 or later
- Docker Compose 1.27 or later
- Java SDK 21
- Spring Boot 3.4.1

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd multi-service-app
