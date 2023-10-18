# Hotel Management Services

Welcome to the Hotel Management Services repository. This project provides a system for managing hotel room operations using an H2 database. Below are the available API endpoints and their functionalities:

## API Endpoints

- **Get All Rooms**
  - **URL:** `/rooms`
  - **Method:** GET
  - **Description:** Get a list of all hotel rooms.

- **Add a Room**
  - **URL:** `/room`
  - **Method:** POST
  - **Description:** Add a new hotel room.
  
- **Get Room by ID**
  - **URL:** `/room/{id}`
  - **Method:** GET
  - **Description:** Retrieve a specific room by its ID.
  
- **Check Room Existence**
  - **URL:** `/room/{id}/exists`
  - **Method:** GET
  - **Description:** Check if a room with a specific ID exists in the database.

- **Get Total Room Count**
  - **URL:** `/rooms/count`
  - **Method:** GET
  - **Description:** Get the total number of hotel rooms available.

- **Delete Room by ID**
  - **URL:** `/room/{id}`
  - **Method:** DELETE
  - **Description:** Delete a room by its ID.

- **Add Multiple Rooms**
  - **URL:** `/rooms`
  - **Method:** POST
  - **Description:** Add multiple hotel rooms in one go.

- **Update Room Type**
  - **URL:** `/room/{id}/{type}`
  - **Method:** PUT
  - **Description:** Update the type of a room by its ID.

- **Get Rooms by Status**
  - **URL:** `/rooms/status/{status}`
  - **Method:** GET
  - **Description:** Get a list of hotel rooms by their availability status.

- **Get Rooms by Status and Type**
  - **URL:** `/rooms/status/{status}/type/{type}`
  - **Method:** GET
  - **Description:** Get rooms by their availability status and room type.

- **Get Rooms by Status, Type, and Price Range**
  - **URL:** `/rooms/status/{status}/type/{type}/priceRange`
  - **Method:** GET
  - **Description:** Get rooms by their availability status, room type, and price range.

- **Get Rooms by Type and Price (Sorted Descending)**
  - **URL:** `/rooms/type/{roomType}`
  - **Method:** GET
  - **Description:** Get rooms of a specific type and sort them by price in descending order.

- **Get Budgeted AC or Non-AC Rooms**
  - **URL:** `/rooms/type1/{roomType1}/type2/{roomType2}`
  - **Method:** GET
  - **Description:** Get budgeted rooms of different types and within a price range.

## Project Information

This project provides
