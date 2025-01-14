# Use the official Python image as the base
FROM python:3.9

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy only the requirements file first for efficient caching
COPY requirements.txt .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the entire project to the working directory
COPY . .

# Expose the port on which the FastAPI app runs
EXPOSE 8000

# Command to run the FastAPI application
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]
