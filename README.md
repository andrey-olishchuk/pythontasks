# Developer Learning Plan

This README outlines a structured learning plan designed to provide a developer with real-world experience in Computer Vision through practical business use cases. The plan focuses on building a system that processes images into vectors, stores them in Qdrant using Dagster pipelines, and develops a FastAPI backend API application exemplified by a "visually similar images" search feature. Additionally, the developer will gain experience with third-party model inference for image analysis. The plan emphasizes hands-on learning with tools like Docker, Docker-Compose, FastAPI, and Dagster.

---

## Learning Objectives
1. **Real-World Computer Vision Experience**
   - Apply Computer Vision techniques to solve practical business problems, with applications tested on Art Paintings examples (Computer Vision in art).
   
2. **Image Processing and Vector Storage**
   - Learn to preprocess images, convert them to vectors, and store them in Qdrant using Dagster pipelines.

3. **FastAPI Backend API Development**
   - Master backend API development with FastAPI, using "visually similar images" search as a practical example.

4. **Third-Party Model Inference**
   - Gain experience integrating custom or open-source models for extracting patterns and objects from images.

5. **Tool Proficiency**
   - Develop skills in Docker, Docker-Compose, FastAPI, and Dagster.

---

## Development Plan

### Phase 1: Environment Setup and Initial Pipeline
1. Learn Docker basics and containerization.
2. Explore Docker-Compose for multi-container setups.
3. Set up Docker-Compose with Dagster web service, Dagster daemon, and Qdrant.
4. Create a simple "Hello World" Dagster pipeline to verify setup.
5. Prepare sample image data (e.g., Art Paintings) for training and testing.

**Goal**: Establish a working environment and prepare data for Computer Vision tasks.

---

### Phase 2: Image Preprocessing and Vector Storage Pipeline
6. Research image preprocessing techniques (e.g., resizing, normalization).
7. Implement image preprocessing in a Dagster pipeline to unify sizes.
8. Select a method/library to transform images into vector data.
9. Extend the pipeline to convert preprocessed images to vectors.
10. Integrate Qdrant into the pipeline to store vector data.

**Goal**: Build a robust pipeline for image preprocessing and vector storage.

---

### Phase 3: FastAPI Application for Similar Image Search
11. Study FastAPI basics for backend API development.
12. Design a FastAPI application with an `/analogues` endpoint.
13. Implement the `/analogues` endpoint to search for visually similar images using Qdrant.
14. Test the endpoint with sample Art Paintings queries.

**Goal**: Create a FastAPI backend API and gain experience searching vector storage.

---

### Phase 4: Advanced FastAPI Endpoints with Model Inference
15. Research custom or open-source models for image analysis (e.g., object detection, pattern extraction in art).
16. Select and integrate a model for inference into the workflow.
17. Create additional FastAPI endpoints (e.g., `/patterns`, `/objects`) to extract features from images.
18. Test the new endpoints with real-world Art Paintings examples.

**Goal**: Enhance the FastAPI application with model inference for advanced Computer Vision tasks.

---

### Phase 5: Integration and Deployment
19. Integrate the FastAPI app, Dagster pipelines, and Qdrant into a unified system.
20. Update Docker-Compose to run the complete application.
21. Test the end-to-end workflow with real business-case scenarios (e.g., Art Paintings analysis).
22. Optimize performance and address any issues.

**Goal**: Deliver a fully functional Computer Vision system.

---

### Phase 6: Finalization
23. Document the system architecture and API endpoints.
24. Write setup and usage instructions for the project.
25. Create two repositories:
    - **Data Pipelines Repository**: Contains Dagster pipelines, licensed under MIT, with full documentation.
    - **FastAPI Core Repository**: Contains the FastAPI application, licensed under MIT, with full documentation.
26. Deploy a demo version showcasing real-world use cases (e.g., Art Paintings).

**Goal**: Complete the project with clear documentation, open-source repositories, and a deployable demo.

---

## Tools to Master
- **Docker**: Containerization for consistent environments.
- **Docker-Compose**: Multi-container orchestration.
- **FastAPI**: Backend API development.
- **Dagster**: Data pipeline orchestration.

---

## Main Focus
This plan prioritizes real-world experience in Computer Vision by tackling practical business problems, such as image similarity search and feature extraction, with a focus on Art Paintings as a testing domain. FastAPI is used as a learning vehicle for backend API development, exemplified by the "visually similar images" use case.

---

## Getting Started

To get started, follow the steps outlined in the project documentation:

- **Step 1** ([DATA.md](DATA.md)):  
  - **Real-World Computer Vision Experience** – Apply Computer Vision techniques to solve practical business problems, with applications tested on art paintings (Computer Vision in art).  
  - **Image Processing and Vector Storage** – Learn to preprocess images, convert them to vectors, and store them in Qdrant using Dagster pipelines.  

- **Step 2** ([STAT.md](STAT.md)):  
  - **FastAPI Backend API Development** – Master backend API development with FastAPI, using "visually similar images" search as a practical example.  
  - **Third-Party Model Inference** – Gain experience integrating custom or open-source models for extracting patterns and objects from images.  
