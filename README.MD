# Cardea Project Readme

This project was developed using Webflow, a no-code platform that allowed for rapid development and deployment of complex components and custom script tags. Despite the ease of use provided by Webflow, the reliance on custom components and scripts has introduced some maintenance challenges.

## Key Features

### Conditional Forms and Premium Calculator
Check out `insurance.html` for examples of our conditional forms and premium calculator. These forms adapt based on user input, providing a dynamic and intuitive experience.

### Complex Multistep Forms
Our `mandat.html` page features intricate multistep forms, designed to guide users through detailed processes seamlessly.

### Script Tags
Initially, Webflow imposed a 10,000-character limit on script tags, which posed significant challenges during development. Fortunately, this limit has since been increased to 50,000 characters, greatly enhancing code readability and maintainability.

## Backend Infrastructure

Our backend is robustly built on AWS, ensuring scalability and reliability. Here are some of the key AWS services we leverage:

- **AWS Lambda**: For serverless computing, handling various backend functionalities.
- **AWS Cognito**: Manages user authentication and login.
- **AWS S3 Buckets**: Securely stores all created documents.
- **AWS Elastic Container Registry**: Robotics for Premium Calculator
- **AWS API Gateway**: Used for the Frontend to communicate with the backend.
- **DynamoDB & Planetscale**: Storage of data, Formdata is stored in SQL Database in Planetscale, while Robotic stores its data into a DynamoDB.
- **Email and Notifications**: All communications are handled via AWS services.

## Accessing the Project

If you would like to dive deeper into the project, you can request access to the Webflow project by sending an email to [marc.robin.weber@gmail.com](mailto:marc.robin.weber@gmail.com).

## Notes

- **Maintenance**: Given that this project was developed with a no-code solution, maintaining the code can be more challenging. However, with the recent increase in the script tag character limit, the readability and manageability of the code have significantly improved.

Feel free to explore the project and reach out if you have any questions or need further assistance or if you wish to have viewing access to the Project on Webflow.

Marc