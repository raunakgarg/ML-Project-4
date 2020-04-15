# ML-Project-4
Face recognition with lambda and aws recognition
# ## Celebritiy Rekcognition

# ### Goal
# The goal of the below case study, is to create an application that detects celebrieties in an image and stores the name of the first celebrity a in database for future purposes.
# 
# Below are the sequence of steps that you will be doing:
# 
# #### Preparatory Phase:
# 
# 1. Use CLI to create
#     - EC2 instance
#     - RDS instance
#     - S3 bucket
# 2. Create appropriate role for each service used in the application
# 3. Create an EC2 instance with Jupyter notebook installed
# 
# 
# #### Implementation phase:
# 
# 1. Upload an image in the S3 bucket
# 2. Create a Lambda function that calls Amazon Rekognition service to detect the celebrities in the image.
# 3. Invoke the Lambda function to extract the celebrity in the image.
# 4. Store the file name and celebrity name in RDS database
# 6. Retrieve the list of all images and details from the database and display in the notebook.
