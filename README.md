This project requires the development of a web application using REACT and Node.js, with a PostgreSQL database backend. The application is designed to handle data management tasks, including creating records, displaying them in a user-friendly interface, and providing search, pagination, and sorting functionalities.

To begin, the application will generate 50 records in the PostgreSQL database. These records will contain various fields such as serial number (sno), customer name, age, phone number, location, and a timestamp indicating the date and time the record was created. The data generated for these records will be dummy data, created for testing and demonstration purposes.

The frontend of the application will be built using REACT, a popular JavaScript library for building user interfaces. The REACT components will provide the structure and interactivity of the single-page application. The main page of the application will display the data from the database in a tabular format, allowing users to view multiple records at once.

The table will include options for search, pagination, and sorting. The search functionality will enable users to search for records based on the customer's name or location. This feature enhances the usability of the application by allowing users to quickly find relevant information within the dataset. Additionally, the pagination feature will limit the number of records displayed on each page to 20, improving the performance and readability of the application.

One unique aspect of this project is the display of the created_at timestamp data. The timestamp will be split into two separate columns, one for the date and one for the time. This separation improves the readability and usability of the data, making it easier for users to understand when each record was created.

Furthermore, users will have the option to sort the displayed data by either the date or time column. This sorting functionality allows users to organize the data according to their preferences, facilitating easier analysis and understanding of the dataset.

Overall, this project aims to create a user-friendly and efficient web application for managing and displaying data from a PostgreSQL database. By leveraging REACT and Node.js technologies, the application will provide a seamless user experience while effectively handling large datasets and providing essential data management functionalities.
