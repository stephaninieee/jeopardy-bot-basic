# Hands-on Lab: Build a Chatbot with Amazon Lex V2 and AWS Lambda
[Slide](https://drive.google.com/file/d/1yzpVHKieUcfWbokH5tZ9gAKnYiz6dsEK/view?usp=sharing  )

This section of the workshop is dedicated to guiding you through the process of building your chatbot using Amazon Lex V2 and AWS Lambda. By the end of this lab, you will have a functional chatbot capable of understanding and responding to specific user inputs.

## Step-by-Step Guide

### 1. Setting Up Amazon Lex V2

- **Introduction to Lex:** Begin by understanding the core concepts of Amazon Lex, such as intents, slots, and fulfillment.
- **Creating Your Bot:** Navigate to the Amazon Lex V2 console and create a new bot. Use the provided naming conventions, for example, `Jeopardy_20230512`, to keep your project organized.

### 2. Designing Your Chatbot

- **Defining Intents and Slots:** Define the intents your chatbot needs to fulfill, such as `CheckScore` or `PlayGame`. Add the necessary slots that will capture user inputs.
- **Sample Utterances:** Provide sample utterances that users might say to trigger the intents. This helps Lex understand how to map user inputs to the correct intent.

### 3. Integrating AWS Lambda

- **Creating a Lambda Function:** Go to the AWS Lambda console and create a new function. This function will process the user's input and provide responses.
- **Function Code:** Use the provided `lambda_function.py` script or write your logic based on the workshop's requirements. Please make sure your code correctly handles the intents and returns appropriate responses.
- **Testing Your Function:** Before integrating with Lex, test your Lambda function using the AWS Lambda console to ensure it behaves as expected.

### 4. Connecting Lex and Lambda

- **Fulfillment:** Set up your bot's intents to use the AWS Lambda function for fulfillment. This links the user's input with the logic processed by Lambda.
- **Testing the Integration:** Use the Amazon Lex console to test the entire chatbot flow. Ensure that when an intent is triggered, the Lambda function processes the request and returns the correct response.

### 5. Deployment and Testing

- **Deploy Your Bot:** Follow the instructions to deploy your chatbot. This may involve setting up channels through which users can interact with your bot.
- **Interactive Testing:** Engage with your chatbot. Start with the sample utterances and then try other inputs to see how it responds. Make adjustments as necessary to improve the interaction.

## Resources

- [Amazon Lex Documentation](https://docs.aws.amazon.com/lex/)
- [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/)
- [Lab Resources Shortlink](https://shorturl.at/abfY1)
- [Event Engine Guide Shortlink](https://shorturl.at/vCJL0)


