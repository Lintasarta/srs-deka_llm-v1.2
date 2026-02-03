# Software Interface

Deka LLM product hosted on the portal ai.cloudeka.id and the backend services supporting it, including the integration of Lite LLM for processing user queries. It covers the software components involved, data flow, communication protocols, and data sharing mechanisms.

- **Platform: Kubernetes (Version: 1.24+)**  
  Service Portal is deployed on Kubernetes, which ensures efficient orchestration and scalability of containers. Kubernetes manages the deployment, scaling, and lifecycle of backend service and other associated microservices.

- **Backend: Lite LLM (Version: 1.51)**  
  Our backend leverages Lite LLM, a streamlined and efficient version of our language model, to power the Deka LLM product. Lite LLM is designed to perform advanced natural language processing tasks, such as text generation and question answering, with optimized resource usage. This integration allows the backend to handle user requests seamlessly, delivering high-quality responses quickly while maintaining scalability and efficiency.

- **Database: PostgreSQL (Version: 14+)**  
  The backend stores user data, query logs, and configuration settings in a PostgreSQL database.
