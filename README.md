# Milvus Vector Database Demo

This is a sample application that demonstrates how to create a collection in a Milvus vector database and perform vector search operations. Milvus is an open-source vector database that is highly reliable for large-scale vector similarity search and analytics.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/).
- You have installed [Python3](https://www.python.org/downloads/).

## Setup and Installation

Follow these steps to get your Python environment set up and the Docker containers running:

1. **Clone the repository**

   First, clone this repository to your local machine using git:

   ```
   git clone https://github.com/Prajwalrk97/milvus-vector-database-demo.git
   ```

   Navigate to the project directory:

   ```
   cd milvus-vector-database-demo
   ```

2. **Pull and create Docker containers**

   Run the following command to pull the necessary Docker images and spin up the containers:

   ```
   docker-compose up -d
   ```

   This command will start the Docker containers in detached mode. You can check the status of the containers with `docker ps`.

3. **Create a Python virtual environment**

   It's a good practice to create a virtual environment for your Python project. This keeps your project's dependencies isolated from other projects. Use the following command to create a new virtual environment in your project directory:

   ```
   python -m venv .venv
   ```

   This command creates a new virtual environment in a directory named `.venv`.

4. **Activate the virtual environment**

   Before you can start installing or using packages in your virtual environment you’ll need to activate it. Activating a virtual environment will put the virtual environment-specific `python` and `pip` executables into your shell’s `PATH`.

   On macOS and Linux:

   ```
   source .venv/bin/activate
   ```

   On Windows:

   ```
   .\.venv\Scripts\activate
   ```

5. **Install the required Python packages**

   With your virtual environment activated, you can now install the required Python packages using `pip`:

   ```
   pip install -r requirements.txt
   ```

   This command installs all the packages listed in the `requirements.txt` file.

You're now ready to run the application!

## Running the Application

To run the application, use the interactive jupyter notebook - "milvus_vector_base_sample.ipynb"
The Milvus vector database will be running on port 19530.

## Conclusion

This guide provided a step-by-step process to set up and run the Milvus vector database demo application. You should now have a functioning local development environment and be able to interact with a Milvus vector database. Happy coding!