# RentalFlix Movie Rental Service

## Entity-Relationship Diagram (ERD)

Below is the Entity-Relationship Diagram (ERD) for the RentalFlix movie rental service. This diagram outlines the key entities and their relationships within the system:

![ERD](./images/RentalFlix%20ERD.png)

### Key Entities and Relationships

- **Movie**: Represents the movies available for rent. Each movie can have multiple formats.
- **MovieFormat**: Represents different formats of a movie (e.g., DVD, Blu-ray, Digital). Each format is linked to a specific movie and has a unique identifier and quantity available.
- **Customer**: Represents the customers of RentalFlix. Each customer can have multiple rentals and reservations.
- **Rental**: Tracks the rental records, including which customer rented which movie format, along with the rental and return dates.
- **Reservation**: Tracks the reservation records, indicating which customer reserved which movie and the status of the reservation (active, fulfilled, canceled).

### Relationships

- **One Movie can have multiple MovieFormats** (One-to-Many)
- **One Customer can have multiple Rentals** (One-to-Many)
- **Many Rentals can be associated with one MovieFormat** (Many-to-One)
- **One Movie can have multiple Reservations** (One-to-Many)
- **One Customer can have multiple Reservations** (One-to-Many)

This ERD provides a clear visual representation of how the different entities interact within the RentalFlix system, ensuring efficient management of the movie rental service.
