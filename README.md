# Manager Library — Public Presentation Site

## Overview

This repository contains the documentation for the public presentation site of **Manager Library**, a library management system designed to organize books, members, loans, and related library operations.

The public presentation site is intended to introduce the project, explain its purpose, describe its main capabilities, and provide general information about the system.

This repository is part of the Manager Library project, which is organized into separate repositories according to their responsibilities.

## Purpose

The purpose of this repository is to define and document the role of the public presentation site within the Manager Library project.

The site provides general information about the project for visitors and stakeholders. It is separate from the application interface used to manage library operations and does not directly communicate with the backend API.

## Scope

The public presentation site is intended to cover the following areas:

- **Project introduction:** Explain what Manager Library is and the problem it addresses.
- **System overview:** Describe the main purpose and general capabilities of the library management system.
- **Project information:** Present relevant information about the system and its organization.
- **Repository separation:** Clarify the distinction between the public presentation site, the React application, and the Laravel API.

### Out of Scope

The public presentation site is not responsible for:

- Managing books, categories, or library members.
- Registering loans or processing book returns.
- Authenticating users or managing access permissions.
- Performing database operations.
- Implementing backend business rules.
- Communicating directly with the backend API.
- Replacing the React application used for library operations.

These responsibilities belong to other components of the Manager Library project.

## Relationship with Other Repositories

Manager Library is organized into six repositories:

| Repository | Responsibility |
|---|---|
| `test-manager-library-3239137-docs` | Project specifications and technical documentation. |
| `test-manager-library-3239137-api` | Backend API implemented with Laravel. |
| `test-manager-library-3239137-app` | React application for library management operations. |
| `test-manager-library-3239137-page` | Public presentation site documented in this repository. |
| `test-manager-library-3239137-infra` | Infrastructure configuration, containers, networking, and database services. |
| `test-manager-library-3239137-tool` | Supporting utilities and test or demonstration data tools. |

Each repository has a separate responsibility. The public presentation site must remain independent of the backend API and the operational application.

## Technology Context

The Manager Library project uses different technologies according to each repository's responsibility.

- **React:** Used by the application repository.
- **Laravel and PHP:** Used by the backend API repository.
- **PostgreSQL:** Used as the project's relational database engine.
- **HTML and CSS:** Relevant technologies for a static presentation site.

This README documents the purpose and boundaries of the presentation site. It does not claim that specific pages, components, or features have already been implemented.

## Development Guidelines

When developing or maintaining this repository, follow these guidelines:

1. Keep the public presentation site focused on introducing the project.
2. Do not duplicate the operational features of the React application.
3. Do not implement backend business logic in the presentation site.
4. Keep project descriptions consistent with the official specifications in the documentation repository.
5. Avoid claiming that features are available unless they have been implemented and verified.
6. Keep the documentation updated when the repository's purpose or responsibilities change.

## Current Repository Status

The repository is intended to contain the public presentation site for Manager Library.

The initial repository structure is intentionally minimal. The actual implementation status must be verified against the files committed to the repository.

This README documents the intended purpose, scope, boundaries, and relationship with the other project repositories. It does not, by itself, indicate that the presentation site has been implemented.

## Related Documentation

For additional information, consult the `test-manager-library-3239137-docs` repository, which contains the project specifications and technical documentation.

Refer to the other repositories for details about the backend API, React application, infrastructure, and supporting tools.
