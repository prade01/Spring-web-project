##                                                               Spring-web-project
# Spring 6 with Ecommerce-Backend and AI-Backend implementation for chat embedding as RAG model for ecommerce products and orders creation updation, deletion and retrieval in Chatbot as PrashruGPT, For Viewing Output used as React Frontned and Spring jsp Frontend.

##                                                               Project Architecture

- <img width="1536" height="1024" alt="Ai_E-Commerce-Architecture1" src="https://github.com/user-attachments/assets/15d3109a-cf79-4e6a-8a92-da7cb1d889f1" />

##                                                                 Project repo url

- Spring login repo url : https://github.com/prade01/Spring-Login.git
- Spring Frontend url : https://github.com/prade01/Spring-Frontend.git
- Spring AI backend url : https://github.com/prade01/Spring-ai-Backend.git
- Spring ecommerce backend url : https://github.com/prade01/Spring-ecommerce-Backend.git
- React Frontend url :  https://github.com/prade01/React-Frontend.git


# Project Summary
- This project is an enterprise-grade e-commerce platform integrating Spring 6, React, Spring Security, JWT authentication, OAuth2 Resource Server, Spring AI, PostgreSQL, MongoDB Atlas, Retrieval Augmented Generation and Ollama-based AI services.
- Provide secure authentication, product management, order processing, AI-powered recommendations, AI chat assistance and scalable service-oriented architecture.

# System Architecture Diagram
- <img width="1536" height="1024" alt="Ai_E-Commerce-Architecture1" src="https://github.com/user-attachments/assets/abbfcb58-4376-46b0-8855-596857a0ddff" />

# Login Module
- Authenticates users using username and password stored in PostgreSQL. Upon successful authentication it generates JWT tokens and stores token details in user session.
- <img width="1920" height="1200" alt="authentication" src="https://github.com/user-attachments/assets/6f29f6ca-6242-49d3-894b-0326843f93a4" />
- <img width="1920" height="1200" alt="authenticated-page" src="https://github.com/user-attachments/assets/c0c449fc-f65e-421d-93aa-68c22c82bb21" />



# JWT Authentication Flow
- User enters credentials, authentication manager validates them, JWT is generated, token is attached to session and forwarded to frontend applications.
- <img width="1920" height="1200" alt="React-unauthorized-page" src="https://github.com/user-attachments/assets/2531c0f4-8709-42a0-97ce-7dbfccaa6b7b" />
- <img width="1920" height="1200" alt="Spring-unauthorized-page" src="https://github.com/user-attachments/assets/faf2c6dd-caf4-4299-9724-d952e5118439" />


# Spring Frontend Module
- Traditional Spring frontend provides dashboards, product catalog management and order management operations including cart, checkout, product administration and AI chatbot integration.
- <img width="1920" height="1200" alt="Spring-authorized-page" src="https://github.com/user-attachments/assets/25aff62c-311f-42e0-a02a-587abcc15730" />
- <img width="1920" height="1200" alt="Spring-product-page" src="https://github.com/user-attachments/assets/33c38dc0-ed9a-49dd-abed-b6e07905f521" />
- <img width="1920" height="1200" alt="Spring-order-page" src="https://github.com/user-attachments/assets/9b957219-3ba6-4087-9257-32fdccd2799f" />
- <img width="1920" height="1200" alt="Spring-product-page" src="https://github.com/user-attachments/assets/77098c8a-ceca-4113-bbe8-3d8c8aadf790" />



# React Frontend Module
- Modern React application provides responsive e-commerce experience including cart, checkout, product administration and AI chatbot integration.
- <img width="1920" height="1200" alt="React-authorized-page" src="https://github.com/user-attachments/assets/97bb90e1-83e5-4129-b150-70be18d8f6cb" />
<img width="1920" height="1200" alt="single-products-view" src="https://github.com/user-attachments/assets/ecfeb18c-a56e-453f-9c01-b6edec121c96" />
<img width="1920" height="1200" alt="React-chatbot-page" src="https://github.com/user-attachments/assets/6bf05778-0b91-4d43-9f20-c0bede951f82" />
<img width="1920" height="1200" alt="ai-description-gen" src="https://github.com/user-attachments/assets/85617d81-6f1c-41c2-a869-4e900d81cf20" />
<img width="1920" height="1200" alt="React-order-page" src="https://github.com/user-attachments/assets/4a344d51-6cce-46c0-87e3-f813b23a8c32" />
<img width="1920" height="1200" alt="cart-page" src="https://github.com/user-attachments/assets/bed69a7e-aeba-44c4-8aa0-f9360b4c3d5b" />
<img width="1920" height="1200" alt="checkout-page" src="https://github.com/user-attachments/assets/73b69ca9-3038-4b6f-a2ef-50d068c2bb3f" />


# Product Management
- Users can view, add, update and delete product records through secured APIs.

# Order Management
- Customers create orders, manage carts and confirm purchases through checkout workflows.

# ecommerce backend
- Dedicated backend exposes REST APIs for products and orders and validates JWT using OAuth2 Resource Server.

# OAuth2 Resource Server Activity
- Every incoming token is validated before business APIs are executed. Invalid tokens receive access denied responses.

# AI backend
- Provides conversational AI, recommendation engine, product description generation, AI image generation and RAG services.

# RAG (Retrieval Augmented Generated)
- Product and order information is retrieved from vector databases and injected into prompts to provide context-aware responses.

# Vector Store design
- Embeddings generated through Ollama local models are stored and searched for semantic similarity.

# Postgres SQL Database Design
- Stores users, roles, products, orders, order items.

# MongoDB Atlas Cloud
- Stores AI knowledge documents, vectorized content, conversation history and unstructured information.

# Embedding with Local Ollama
- Embedding models run locally to generate vectors while reducing cloud dependency.

# Chat Integeration with ollama Cloud
- Cloud-hosted Ollama models provide conversational responses and reasoning capabilities.

# Security Architecture
- JWT, Spring Security, role-based authorization and resource server validation secure the platform.

# Deployment Architecture
- Applications can run independently on separate servers connected through configured service URLs.

# Scalability Consideration
- Services can be scaled individually according to workload characteristics.

# Advantages of Current design
- Separation of concerns, modular deployment and independent evolution of frontend and backend components.

# Future Enhancements
- API Gateway, Service Discovery, Docker, Kubernetes, CI/CD, Observability, Caching and Event Driven Architecture.

# Conclusion
- The platform demonstrates modern enterprise software engineering by combining Spring technologies, React, AI capabilities and cloud databases into a unified e-commerce solution.
