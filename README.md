# Online-Flight-Booking-Management-System-
```md
# ✈️ Online Flight Booking System

An online flight booking system developed using **PHP and MySQL**.

📂 Project Structure

- `index.php` - Home page  
- `login.php` - User login page  
- `book_flight.php` - Flight booking functionality  
- `e_ticket.php` - Generate and view e-tickets  
- `payment.php` - Payment processing  
- `my_flights.php` - User's booked flights  
- `pass_form.php` - Passenger details form  
- `feedback.php` - Feedback submission  

🛠 Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  

📂 Installation & Setup

1. Clone the repository:  
   ```bash
   git clone https://github.com/NehaR1306/Online-Flight-Booking-Management-System-
   ```
2. Import the database:
   - Open **phpMyAdmin**
   - Create a new database (e.g., `flight_booking_db`)
   - Import the provided `.sql` file  

3. Configure database connection in `config.php`:
   ```php
   $servername = "localhost";
   $username = "your_db_username";
   $password = "your_db_password";
   $database = "flight_booking_db";
   ```

4. Run the project:
   - Place the project in `htdocs` (for XAMPP) or `www` (for WAMP)  
   - Start Apache and MySQL  
   - Open `http://localhost/OnlineFlightBooking-PHP/index.php`
