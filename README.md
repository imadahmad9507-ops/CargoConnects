# CargoConnects

> Digital freight and shipment-management platform prototype.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)](https://www.mysql.com/)

## Overview

CargoConnects explores a unified experience for shippers, carriers, drivers, and administrators. The interface combines shipment discovery, tracking, service information, stakeholder portals, and operational workflows.

## Product capabilities

- Shipment tracking by tracking ID
- Admin dashboard and fleet registration
- Client, driver, and truck-owner workflows
- Responsive multi-page frontend
- Flask REST API integration
- MySQL schema designed for logistics workflows
- Animated route and freight-focused visual language

## Architecture

```text
Browser UI (HTML/CSS/JavaScript)
          |
          v
     Flask REST API
          |
          v
       MySQL
```

## Repository hygiene

This public repository is a documentation-first showcase. Private credentials, local database exports, and client-specific configuration are intentionally excluded. Add deployment-specific environment variables through the hosting provider rather than committing them.

## Project status

Prototype / academic engineering project. The next production step would be to add automated tests, environment-based configuration, authentication hardening, and a deployment pipeline.
