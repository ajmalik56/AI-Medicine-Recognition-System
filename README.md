# Medicine-Recognition-System

This Flask web application utilizes Google's Generative AI models to generate detailed medical descriptions for uploaded images. The project, which focuses on medical content generation, incorporates two key models: the Pro-Vision model for in-depth medical descriptions and the Pro model for additional content generation. Upon uploading an image, the application uses the Pro-Vision model to generate comprehensive medical descriptions, ensuring clinical accuracy. Additionally, a validation step with the Pro model ensures that the context is indeed related to the medical field. The user is provided with generated content on successful validation, while the interface prompts for a valid medical image otherwise. The project's user interaction includes uploading images through a simple web form, content generation based on the uploaded images, and a validation step to ensure medical relevance. To maintain security, the application loads the required Google API key from environment variables. Further improvements could involve enhanced error handling, a more user-friendly interface, and thorough documentation for future development and maintenance.

## Built With

 - Google-GenerativeAI
 - Flask

## Getting Started

This will help you understand how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

## Installation Steps


    





6. **Access the Project**
   - Open a web browser or the appropriate client to access the project.<br>

## Installation from DockerHub

If you prefer to use Docker, you can install and run the project using a Docker container from DockerHub:

1. **Pull the Docker Image**
   - Open your terminal or command prompt.
   - Run the following command to pull the Docker image from DockerHub:
     ```
     docker pull kalyan45/movierecommend-app
     ```
     This command downloads the Docker image from the DockerHub.

2. **Run the Docker Container**
   - Start the Docker container by running the following command. Adjust the port mapping as needed:
    
    

3. **Access the Project**
   - Open a web browser or the appropriate client to access the project.<br>

   
## API Key Setup

To use this project, you need an API key from Google Gemini Large Language Model. Follow these steps to obtain and set up your API key:

1. **Get API Key:**
   
   - Follow the instructions to create an account and obtain your API key.

2. **Set Up API Key:**
   - Create a file named `.env` in the project root.
   - Add your API key to the `.env` file:
     ```dotenv
     GOOGLE_API_KEY=your_api_key_here
     ```

   **Note:** Keep your API key confidential. Do not share it publicly or expose it in your code.<br>


## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

• **Report bugs**: If you encounter any bugs, please let us know. Open up an issue and let us know the problem.

• **Contribute code**: If you are a developer and want to contribute, follow the instructions below to get started!

1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes
4. Push to the Branch
5. Open a Pull Request

• **Suggestions**: If you don't want to code but have some awesome ideas, open up an issue explaining some updates or improvements you would like to see!

#### Don't forget to give the project a star! Thanks again!




