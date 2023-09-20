# CHATBOT


# JSGPT Chatbot


![chatbot2](https://github.com/JoseSagwe/CHATBOT/assets/110198843/fb90704d-a667-4c92-8cf3-37194c07be0e)

JSGPT Chatbot is a simple Android chat application that integrates with the OpenAI GPT-3 model to provide natural language understanding and generation capabilities. This chatbot allows users to have conversations with a virtual assistant powered by OpenAI's advanced language model.

## Features
- Real-time chat interface.
- Integration with OpenAI GPT-3 for responses.
- Message categorization between user and chatbot.
- Responsive UI for a smooth chat experience.


## Installation

Follow these steps to set up and run the JSGPT Chatbot app on your Android device:

1. Clone the repository to your local machine:

2. Open the project in Android Studio.

3. Build and run the project on your Android device or emulator.


## Usage

1. Open the JSGPT Chatbot app on your Android device.

2. Start a conversation by typing a message in the message input field and tap the send button.

3. The chatbot will respond with a message generated by the OpenAI GPT-3 model.

4. Continue the conversation by alternating between user and chatbot messages.


## Dependencies

- [OkHttp](https://square.github.io/okhttp/): Used for making HTTP requests to the OpenAI API.
- AndroidX libraries: Used for Android app development components.

## Configuration

To configure the app to work with your OpenAI GPT-3 API, you will need to:

1. Replace `"Bearer API KEY"` in the `callAPI` method of `MainActivity.java` with your actual OpenAI API key.

   ```java
   .header("Authorization", "Bearer YOUR_API_KEY")
   ```

2. Customize the chatbot's behavior and responses by modifying the parameters in the `jsonBody` object within the `callAPI` method.


