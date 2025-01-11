# Lost and Found Application

This Spring Boot application manages a lost and found system.  It allows administrators to upload lost item details from a text file, users to view lost items and claim them, and administrators to view all claims.

## Features

* **Admin Panel:**
    * Upload lost item details from a text file (ItemName, Quantity, Place).  The file should follow a specific format (see below).
    * View all claims made by users.

* **User Panel:**
    * View a list of all lost items.
    * Claim lost items, specifying the item and the quantity claimed.

## Technologies

* Java
* Spring Boot
* Spring Data JPA
* H2 Database (in-memory, for testing; easily configurable for other databases)
* Maven (for build management)
* JUnit/Mockito (for testing)

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
