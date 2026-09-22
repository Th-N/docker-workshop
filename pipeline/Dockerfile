FROM python:3.13.11-slim

# Set up image by installing prerequisites
RUN pip install pandas pyarrow

# Create the destination directory inside the image
WORKDIR /code
COPY pipeline.py .

# Defines what to do first when the container runs
ENTRYPOINT ["python", "pipeline.py"]