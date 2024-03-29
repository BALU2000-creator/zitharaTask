# Customer Data Management Application

This application is designed to manage and display customer data from a PostgreSQL database. It consists of a frontend built with React.js and a backend server built with Node.js and Express.js.

## Features

- Display a table of customer data including name, age, phone number, location, date, and time of creation.
- Search functionality to filter customers by name and location.
- Sort functionality to sort customers by date or time of creation, in ascending or descending order.
- Pagination to navigate through large sets of customer data.

## Technologies Used

- **Frontend:**
  - React.js: A JavaScript library for building user interfaces.
  - Axios: A promise-based HTTP client for making requests to the backend server.
  - CSS: Styling the components.

- **Backend:**
  - Node.js: A JavaScript runtime for building server-side applications.
  - Express.js: A web application framework for Node.js for building APIs.
  - PostgreSQL: A relational database management system.
  - pg (node-postgres): A PostgreSQL client for Node.js.

## Setup

1. **Clone the Repository:**
   ```
   git clone https://github.com/yourusername/customer-data-management.git
   cd customer-data-management
   ```

2. **Install Dependencies:**
   - Navigate to the `client` directory and install frontend dependencies:
     ```
     cd client
     npm install
     ```
   - Navigate to the `server` directory and install backend dependencies:
     ```
     cd ../server
     npm install
     ```

3. **Database Setup:**
   - Set up a PostgreSQL database and configure the connection details in the server's `index.js` file.
   - Import the provided SQL file `customers.sql` into your database to create the necessary table and populate it with sample data.

4. **Run the Application:**
   - Start the backend server:
     ```
     npm start
     ```
   - Start the frontend:
     ```
     cd ../client
     npm start
     ```
   The application should now be running. Open your browser and navigate to `http://localhost:3000` to view it.

## Usage

- Upon loading the application, you will see a table displaying customer data.
- Use the search filters to filter customers by name or location.
- Use the sort dropdowns to sort customers by date or time of creation, in ascending or descending order.
- Pagination buttons are available to navigate through multiple pages of customer data.

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request detailing your contributions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the developers of React.js, Express.js, and PostgreSQL for their amazing tools and documentation.
- Special thanks to [OpenAI](https://openai.com) for providing the language model used to generate this README.

Feel free to customize this README to suit your project's specific needs.
