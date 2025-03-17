# Developer Learning Plan: Computer Vision with Dagster and Qdrant

## Objective
Your task is to implement a practical Computer Vision pipeline that processes images of art paintings, converts them into vector representations, and stores them in Qdrant. This hands-on project will provide experience with image preprocessing, vector storage, and Dagster-based data pipelines.

## Learning Goals
1. **Real-World Computer Vision Experience**  
   - Apply Computer Vision techniques to solve a practical business problem related to art.
   - Build an image processing pipeline for artwork analysis.

2. **Image Processing and Vector Storage**  
   - Preprocess images to maintain their colors but normalize their sizes.
   - Convert images to vector representations.
   - Store the resulting vectors in Qdrant using Dagster pipelines.

---

## Task Instructions

### 1. **Set Up the Environment Using Docker Compose**
- Create a `docker-compose.yml` file to orchestrate the required services.
- Ensure the setup includes:
  - **Dagster Webservice**: To visualize and manage the pipeline.
  - **Dagster Daemon**: To execute the pipeline runs.
  - **Qdrant**: As a vector storage solution.
- Run `docker-compose up` and verify that all services start correctly.

### 2. **Implement Image Preprocessing Pipeline**
- Develop a mechanism to load images from a local folder.
- Ensure the preprocessing step:
  - Retains the original colors of the images.
  - Resizes all images so that the longest side is the same across all images.
- Save the processed images before conversion for debugging purposes.

### 3. **Convert Images to Vector Representations**
- Implement logic to transform each image into a numerical vector.
- Use the pixel color matrix as the vector representation.
- Ensure that the vectors preserve meaningful image information.

### 4. **Store Image Vectors in Qdrant**
- Set up a connection to Qdrant from your Dagster pipeline.
- Define a collection in Qdrant where the image vectors will be stored.
- Ensure that each image vector is saved with an identifier (e.g., image filename or hash).

### 5. **Run and Test the Pipeline**
- Execute the Dagster pipeline to process images and store vectors in Qdrant.
- Verify that the vectors appear in the Qdrant database.
- Implement a simple dashboard or API endpoint to confirm the stored data.

### 6. **Acceptance Criteria**
- A fully functional `docker-compose.yml` file that sets up all necessary services.
- A Dagster pipeline that:
  - Loads images from a folder.
  - Normalizes their sizes while preserving colors.
  - Converts them into vectors and stores them in Qdrant.
- After running the pipeline, stored vectors should be visible in a `/dashboard` endpoint or visualization tool.

