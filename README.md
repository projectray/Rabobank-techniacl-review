# Lost and Found Application

This is a Spring Boot application for a lost and found system.  The administrators is allowed to upload lost item details from a text file and to view all claims. Users are allowed to view lost items and claim them.

## Features

* **Admin:**
    * Upload lost item details from a text file (ItemName, Quantity, Place).  The file should follow a specific format (see below).
    * View all claims made by users.

* **User:**
    * View a list of all lost items.
    * Claim lost items, specifying the item and the quantity claimed.

## Technologies

* Java
* Spring Boot
* Spring Data JPA
* H2 Database (in-memory, for testing)
* Maven (for build management)
* JUnit/Mockito (for testing)

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/projectray/Rabobank-techniacl-review.git
2. **Build application:**
   Navigate to the project's root directory and run
   ```bash
   mvn clean install
   
