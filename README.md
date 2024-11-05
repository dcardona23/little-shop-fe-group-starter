# Little Shop

### Abstract:
Our project, Little Shop, is a full-stack application that allows users to manage merchants and their items. This app simplifies merchant and item management by providing functionality to create, edit, view, and delete merchant profiles and their associated items. The app makes it easy to view and filter items by merchant, offering a more organized approach to inventory management. 

### Installation Instructions:
- Clone this repository to your local machine.
- Navigate into the project directory.
- Run npm install to install all dependencies.
- Start the application by running npm run dev in the terminal.
- Open http://localhost:5173 (or the URL specified in your terminal) in your browser to view the application.

### Preview of App:
![Little Shop Preview](https://github.com/dcardona23/little-shop-fe-group-starter/blob/main/Little%20Shop.gif)
### Context:

Our team worked on this project over the course of approximately one week. We focused on enchancing the user experience and improving the efficienty of the existing frontend code. Specifically, we refactored functions to improve readability and performance, and we added CSS styling to ensure a visually appealing and user-friendly interface. Finally, we added client-side validation to prevent users from adding merchants without the required parameters.  

### Contributors:
* [Bryan Willet](https://github.com/bwillett2003)
* [Danielle Cardona](https://github.com/dcardona23)
* [Jeremiah Ross](https://github.com/Crosswolfv1)
* [Michael OBrien](https://github.com/MiTOBrien)

### Learning Goals:
This project focused on mastering core backend and frontend development practices to create a robust, user-friendly application. Key learning goals included:
- Backend development using Ruby on Rails, ActiveRecord, and SQL, including building efficient database queries to manage one-to-many relationships and provide structured data for the frontend.
- API development and data validation, including exposing CRUD endpoints for database resources, ensuring data integrity through model validation, and handling invalid inputs with appropriate error responses.
- Comprehensive testing for both expected (happy path) and unexpected (sad path) outcomes.
- Utilizing MVC architecture to organize the app, with data logic encapsulated in models, reducing complexity in controllers.
- Frontend enhancements to improve the existing frontend, including enhancing UI styling and refactoring JavaScript code for better readability and functionality.
- Project management utilizing GitHub Projects to track tasks and user stories.

### Wins + Challenges:
Wins:

- Successfully implemented CRUD functionality, making data management more intuitive.
- Implemented an error serializer to streamline error handling and improve code readability.
- Refactored key functions like filterByMerchant and findMerchant, making the code more modular and reusable.
- Improved the app’s UI/UX by adding custom CSS styling.

Challenges:

- It was a challenge to ensure that all database logic was removed from our controllers to maintain a clean MVC structure. This proved challenging because it increased the complexity of our code, but we were committed to ensuring our app adhered to MVC principles and best practices. 
- Refactoring our error handling logic to incorporate an error serializer was a significant challenge, but ultimately a valuable improvement. This change required extensive revisions to existing, functional code, which was both complex and time-consuming. However, implementing the error serializer greatly enhanced the readability and organization of our code, making it well worth the effort. 