# **Boctor - AI Chatbot Doctor**
Boctor is an AI chatbot doctor that provides medical consultations and diagnoses to patients. It was developed as part of a hackathon project, and is designed to provide quick and efficient medical services to patients in need. Boctor makes use of advanced machine learning algorithms and natural language processing to understand patient queries and provide accurate medical advice.

Website Link: https://boctor.vercel.app/

## Technologies Used
Boctor makes use of the following technologies:

- Frontend: Next.js
- Backend: Flask
- Machine Learning: Python, NLTK

## How to Use
To use Boctor, simply visit the [website](https://boctor.vercel.app/) and start chatting with the AI chatbot. Boctor will ask you a series of questions related to your medical condition and provide medical advice based on your answers. Boctor is designed to provide quick and efficient medical services, so you can get the medical help you need without having to leave your home.

## Features
Some of the features of Boctor include:

- Medical Consultation: Boctor provides medical consultation services to patients. It can diagnose medical conditions, provide medical advice, and prescribe medication if necessary.

- Efficient and Accurate: Boctor is designed to be efficient and accurate, providing quick medical services to patients in need.

- Natural Language Processing: Boctor makes use of natural language processing to understand patient queries and provide accurate medical advice.

## Deployment
Boctor is currently deployed using the following technologies:

Frontend: The frontend is deployed on Vercel, a cloud platform for static sites and serverless functions. The Vercel deployment is configured to automatically build and deploy the Next.js frontend whenever changes are pushed to the GitHub repository.

Backend: The backend is running on an AMD instance created on GCP, with the Flask application being served using uWSGI and NGINX.
         The future plan is the deployment to be managed using Docker containers, with the image being built and pushed to Google Container Registry whenever changes are pushed to the GitHub repository.

## Development
Boctor was developed as part of a hackathon project for **GFG Solve For India**, with the goal of creating a tool that could help address the healthcare needs of people around the world. The team used Next.js for the frontend, Flask for the backend, and Python and TensorFlow for the machine learning algorithms.

During the hackathon, the team faced a number of challenges, including:

- Data Collection: In order to develop accurate machine learning models, the team needed to collect a large amount of medical data. This involved working with healthcare providers and patients to collect and label data.
                   We still need more data to train and make it better

- Model Training: Once the minimum data was collected, the team needed to train machine learning models to accurately diagnose medical conditions and provide medical advice. This involved experimenting with different models and tuning hyperparameters to achieve the best results.

- Integration: Finally, the team needed to integrate the frontend, backend, and machine learning components of the project to create a seamless user experience.

Despite these challenges, the team was able to successfully develop Boctor and create a tool that has the potential to improve access to healthcare for people around the world.

## Conclusion
Boctor is an AI chatbot doctor that provides medical consultations and diagnoses to patients. It was developed as part of a hackathon project, with the goal of creating a tool that could help address the healthcare needs of people around the world. With Boctor, patients can get the medical help they need without having to leave their home, and healthcare providers can use the tool to provide efficient and accurate medical services.

Boctor is not meant to replace Doctors but reach where they cannot
