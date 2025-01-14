# Bus_tracking_ESP32
A bus tracking system using an ESP32 with GPS module 
## Technologies Used

- **Tailwind CSS**: Used for designing and styling the user interface.
- **React**: Developed the front-end interface and real-time map tracking.
- **Express**: Built the backend server for handling API requests and managing data.
- **MongoDB**: Used for storing and managing bus route data.
- **Socket.io**: Enabled real-time communication between the server and clients.
- **Google Maps API**: Integrated for displaying and interacting with maps.
- **Azure**: Deployed the application on Azure cloud services for scalability and reliability.
- **NLP and ML**: Utilized Natural Language Processing and Machine Learning for the chatbot functionality.

## Getting Started

To get a copy of this project up and running on your local machine for development and testing purposes, follow these steps:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/your-username/real-time-bus-tracking.git
   ```

2. Install the project dependencies:

   ```shell
   cd real-time-bus-tracking
   npm install
   ```

3. Set up your environment variables, including database connection details, Google Maps API keys, and Azure deployment settings.

4. Start the development server:

   ```shell
   npm start
   ```

5. Access the application by navigating to `http://localhost:3000` in your web browser.

## Project Structure

The project structure is organized as follows:-

- `FrontEnd/`: Contains the React front-end application.
- `BackEnd/`: Houses the Express backend and chatbot logic.
- `BackEnd/models/`: Stores MongoDB schema and models.
- `BackEnd/router/`: Defines API routes.
- `BackEnd/Database/`: Stores MongoDB connections.
- `BackEnd/controllers/`: Contains end-point functionalities.
