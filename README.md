# Robo Advisor for Retirement Plans

In this homework assignment, a Robo Advisor was created using Amazon Web Services and Python, to recommend an asset allocation for a retirement plan. The Robo Advisor was published and deployed on Slack as an app for users to access. 


1. [Initial Robo Advisor Configuration](Initial-Robo-Advisor-Configuration)

2. [Build and Test the Robo Advisor](Build-and-Test-the-Robo-Advisor)

3. [Deploy the Robo Advisor on Slack](Deploy-the-Robo-Advisor-on-Slack) 

4. [Enhance the Robo Advisor with an Amazon Lambda Function](Enhance-the-Robo-Advisor-with-an-Amazon-Lambda-Function)

5. [Robo Advisor in Action!](Robo-Advisor-in-Action!)


### Initial Robo Advisor Configuration

  An [Amazon Lex Bot](https://us-west-2.console.aws.amazon.com/lex/home?region=us-west-2) was created with a single intent named RecommendPortfolio to establish a conversation about the requirement inputs needed to suggest an asset allocation mix. 
  
  A few sample utterances and slots were established
  
  ![utterances](Images/utterances.png)        ![slots](Images/slots.png)

  
### Build and Test the Robo Advisor

The Robo Advisor was built and tested to ensure it is responding accurately with the user. 

![Test Video](Images/test.gif)

  
### Deploy the Robo Advisor on Slack: 
 
  The bot was published and deployed as a Robo Advisor Slack app. 
  
  ![publish](Images/publish.png)
  
  ![slack](Images/slack.png}
 
###  Enhance the Robo Advisor with an Amazon Lambda Function

  Create an Amazon Lambda function that validates the user's input and returns the investment portfolio recommendation. This task includes testing the Amazon Lambda function and making the integration with the bot.
  Deploy the Robo Advisor Powered by Amazon Lambda: Publish a new version of your bot that includes the new Amazon Lambda function, also test the new version of your bot on Slack.
  
  ![lambda](Images/lambda.png)
  
  ### Robo Advisor in Action! 

![Video](Images/Media1.gif)
