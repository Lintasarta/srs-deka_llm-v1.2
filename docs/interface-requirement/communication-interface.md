# Communication Interface

- **Frontend to Backend**  
  The portal communicates with the backend using HTTPS REST API calls, ensuring secure transmission of data between the frontend and the backend. The communication may also include authentication tokens or session identifiers for secure user interactions.

- **Backend to Lite LLM:**  
  The backend communicates with the Lite LLM model using a REST API The backend sends formatted user queries to the Lite LLM, which processes the input and returns a response. Communication between these components is encrypted to ensure privacy and security.

- **Backend to PostgreSQL:**  
  The backend interacts with the PostgreSQL database over a secure connection using the standard PostgreSQL protocol. This allows the backend to store and retrieve data related to user interactions, model configurations, and other application-specific information.
