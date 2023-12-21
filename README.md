# RailwayReservationjava

### Classes:

1. **Train Class:**
   - Represents a train with attributes like name, source, destination, departure time, passenger strength, and train number.
   - Provides getter and setter methods for accessing and modifying the attributes.

2. **ReservationSystem Class:**
   - Manages the railway reservation system.
   - Contains an ArrayList of trains and initializes it with sample data.
   - Provides methods for displaying available trains, checking seat availability, booking tickets, canceling tickets, and displaying ticket details.

### Main Class:

3. **Main Class:**
   - Handles user input and serves as the entry point for the program.
   - Utilizes the `ReservationSystem` class to interact with the railway reservation system.

### Execution Flow:

4. **User Interface:**
   - The program welcomes the user and presents a menu with options to check available trains, seat availability, book a ticket, cancel a ticket, display ticket details, and exit.

5. **Menu Options:**
   - **Check Available Trains (Option 1):**
     - Takes user input for source and destination stations.
     - Displays available trains based on the provided stations.

   - **Check Seat Availability (Option 2):**
     - Takes user input for the train number.
     - Displays the available seats for the specified train.

   - **Book a Ticket (Option 3):**
     - Takes user input for the train number and passenger name.
     - Books a ticket if seats are available.

   - **Cancel a Ticket (Option 4):**
     - Takes user input for the train number and passenger name.
     - Cancels a booked ticket if the specified conditions are met.

   - **Display Ticket Details (Option 5):**
     - Takes user input for the train number and passenger name.
     - Displays details of a booked ticket.

   - **Exit (Option 6):**
     - Exits the program.

6. **Looping Menu:**
   - The program runs in a loop, allowing the user to perform multiple operations until choosing the exit option.

### Usage:

7. **User Input:**
   - The program prompts the user to enter various inputs such as source and destination stations, train numbers, and passenger names.

8. **Feedback:**
   - Provides feedback messages for successful operations or informs the user if an operation fails.
