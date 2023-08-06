# Funliners - An Amazon Alexa Skill
Funliners is a simple Alexa skill that provides entertaining tongue twisters whenever you ask for them. This skill demonstrates the use of the Alexa Skills Kit, a serverless backend, and the Amazon Lambda function to create a delightful user experience.

## Results
![Result_1](https://github.com/shivamdeshmukh/Tongue_Twister_AI/assets/72214326/8668df1b-9bbf-453f-afb1-743422f63f77)


## Getting Started
To use the Funliners Alexa skill, follow these steps:

1. Open the Alexa Developer Console and click on the Alexa link.
2. Create a new skill:
   1. Skill name: Funliners
   2. Language: English (IN)
   3. Skill model: Custom
   4. Template: Fact Skill
   5. Invocation name: "fun liners"
3. Define Intents:
   1. Built-in intents: Cancellntent, HelpIntent, StopIntent, FallBackIntent, NavigateHomeIntent
   2. Create a new intent: GetNewFactIntent with sample utterances like:
      1. tell me a fun liner
      2. give me a tongue twister
      3. sing a tongue twister
      4. tell me a tongue twister phrase
      5. tell me a twister
      6. ...
4. Create another intent: AnotherFactIntent with sample utterances like:
   1. different one
   2. next one
   3. another fun liner
   4. another tongue twister
5. Edit other intents according to your preferences.
6. Build the skill.
7. Configure Endpoints:
    1. Deploy the Lambda function in different regions using the Serverless Framework.
    2. Add the ARNs of these functions in the Endpoints of your skill.
8. Test the skill in the developer console.

## Supported Languages
Funliners can be used in multiple languages including:
- English (IN)
- English (US)
- English (CA)
- English (EU)
- ...

## Contributors
Shivam deshmukh

## License
This project is licensed under the MIT License.

## Acknowledgments
This project was inspired by the desire to create a fun and interactive Alexa skill.
Thanks to the Alexa Skills Kit and Amazon Lambda for making development easier.
