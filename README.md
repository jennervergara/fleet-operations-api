# Fleet Operations REST API

## Overview

Fleet Operations REST API is a demonstration backend application designed to manage fleet operations, including trucks, drivers, fuel transactions, and toll transactions.

The project is being developed with Laravel and PostgreSQL, following REST API principles and relational database design practices.

It is an independent portfolio project inspired by common business requirements in the transportation industry. It uses synthetic data and contains no proprietary company information.

## Technology Stack

- PHP
- Laravel
- PostgreSQL
- REST API
- JSON
- SQL
- Git

## Main Features

The project is designed to include:

- Truck management
- Driver management
- Fuel transaction management
- Toll transaction management
- Relational database design
- Input validation
- API authentication and authorization
- Pagination and filtering
- Error handling
- Database query optimization

## Database Structure

The initial database design includes:

- `trucks`
- `drivers`
- `fuel_transactions`
- `toll_transactions`

### Relationships

- One truck can have many fuel transactions.
- One truck can have many toll transactions.
- Each transaction belongs to a specific truck.
- Drivers can be associated with trucks.

## Planned API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | /api/trucks | List trucks |
| GET | /api/trucks/{id} | Get truck details |
| POST | /api/trucks | Create a truck |
| PUT | /api/trucks/{id} | Update a truck |
| DELETE | /api/trucks/{id} | Delete a truck |
| GET | /api/trucks/{id}/fuel | Get fuel transactions |
| GET | /api/trucks/{id}/tolls | Get toll transactions |

## Development Goals

This project will demonstrate practical knowledge of:

- Backend application development.
- REST API design and implementation.
- PostgreSQL database architecture.
- Laravel Eloquent relationships.
- SQL query optimization and indexing.
- API validation and error handling.
- Secure application development.
- Git version control.

## Project Status

In development.

More features, documentation, and implementation examples will be added as the project progresses.
