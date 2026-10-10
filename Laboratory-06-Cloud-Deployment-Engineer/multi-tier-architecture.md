# Multi-Tier Architecture Overview

## Definition of a Two-Tier Architecture
A two-tier architecture is a software design pattern where an application is split into two distinct, communicating layers: the presentation/application tier and the data tier. In this deployment, the Nextcloud web container acts as the application tier, while the MariaDB container acts as the database tier.

## The Tiers
* **The Web/Application Tier:** Serves the user interface, handles incoming HTTP requests from users, processes application logic, and renders the web pages.
* **The Database Tier:** Responsible for storing persistent data securely, including user credentials, configuration settings, and file metadata.

## Why Separate Them?
Separating the web server and the database into two distinct containers rather than packing them into a single container provides vital architectural advantages. It enhances scalability, allowing cloud engineers to scale or update the web application tier independently of the database storage. It also improves security and fault tolerance, isolating database transactions and ensuring that a failure or update in the web frontend does not compromise the underlying database integrity.
