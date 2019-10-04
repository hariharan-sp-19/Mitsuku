# Mitsuku
Alexa Skiil using the Mitsuku Chatbot AI - https://www.hackster.io/hariharan/mitsuku-62b1fc

Lambda Function:

1.Create the Lambda function , the RunTime is Node.js 4.3
	It uses a node modules(mitsuku-api),so it has to be zipped and uploaded to the aws.amazon
2.Handler:index.handler
3.Role : Choose existing role	
4.Existing role:lambda_basic_execution
5.Check the details and create the Function.

Alexa SKill

1.Set the name of the skill,invocation name for the skill
2.Set the Intent Scheme and the sample utterances
3.Copy paste the ARN of the lambda function that you wrote, In skill configuration menu to the Service Endpoint.
4.Save and test the skill and Start using the skill.
