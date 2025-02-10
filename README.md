![image](https://github.com/user-attachments/assets/7f6f1e1a-f549-4d6f-971c-fd936579e8f2)

Translator is a web application software tool that facilitate the translation of text from one language to another language using ReactJS. This application allows users to give input Text and select input and output language Format from the list of languages and uses Microsoft Translator API. Users can also reverse the source and target languages and clear the input text. The component provides a user-friendly interface for language translation, with dynamic updates and error handling. This application is implemented using ReactJS and has a simple and responsive UI.

Prerequisites and Technologies:

ReactJS
CSS
Functional Components in React
Rapid API
Approach/Functionalities:

This project basically implements functional components and manages states. This application uses the Microsoft Translator API for language translation, making POST requests with the input text and language preferences. Upon receiving the response, the translated text is updated in the component's state, and loading spinners are displayed during the API call. The component's interface allows users to select languages, input text, translate, and reverse language selection. If API call is rejected then it shows an error message during translation.

Steps to create the application:

Step 1: Set up React project using the command

npx create-react-app <<name of project>>
Step 2: Navigate to the project folder using

cd <<Name_of_project>>
Step 3: Create a folder “components” and add three new files in it and name them as Translator.js, language.json and Translator.css.

Project Structure
The updated dependencies in package.json will look like this:

"dependencies": {
         "@testing-library/jest-dom": "^5.17.0",
         "@testing-library/react": "^13.4.0",
         "@testing-library/user-event": "^13.5.0",
         "react": "^18.2.0",
         "react-dom": "^18.2.0",
         "react-scripts": "5.0.1",
         "web-vitals": "^2.1.4"
}                                                                                                                                                                                                                          
