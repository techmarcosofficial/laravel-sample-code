# 🚀 Laravel Application Overview

This Laravel-based application is structured around modular, reusable, and service-driven principles. Below is an overview of the key components including **Controllers**, **Models**, **Form Requests**, and **Traits** used across the project.

---

## 📁 Project Structure

### 🧠 Controllers

Manage business logic and handle HTTP requests.

| Controller                | Description                                                                      |
|---------------------------|----------------------------------------------------------------------------------|
| `HubspotController.php`   | Integrates with HubSpot to fetch and push records via API                        |
| `OrganizationController.php` | Manages organization data including creation, editing, and profile handling     |

---

### 🗃 Models

Represent Eloquent models tied to your database.

| Model         | Description                |
|---------------|----------------------------|
| `User.php`    | Handles user authentication and relationships |

---

### ✅ Form Requests

Encapsulate form validation logic for incoming requests.

| Request Class             | Purpose                                   |
|---------------------------|-------------------------------------------|
| `OrganizationRequest.php` | Validates organization-related form input |

---

### 🔁 Traits

Reusable methods shared across controllers and services.

| Trait Name        | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `ExportCsv.php`   | Generates and exports CSV files with proper headers and formatting          |
| `ImageUpload.php` | Handles image uploads and generates thumbnails in custom sizes              |
| `LatLng.php`      | Retrieves latitude and longitude using Google Maps Geocoding API            |
| `Mailer.php`      | Sends templated emails with dynamic content and recipient configuration     |

---

## 🛠 Tech Stack

- **Laravel** (version 9+ recommended)
- **MySQL / MariaDB**
- **Composer** for dependency management
- **Blade** templating engine
- **HubSpot API** integration
- **Google Maps API** for geolocation

---

## 📁 Directory Layout (Simplified)

