# OpenAI_AWSEC2 Task

There is project created where using openAI AWS EC2 instance details are fetched.Below are the steps followed for the successful execution.

1.Import boto3 ,os and openai in below code.
Then,provide AWS access key ,Secret key and default region.
I have hidden openai.api_key to avoid misuse as you can use your own chatGPT key

<img width="728" alt="image" src="https://github.com/aakkat/OpenAILangchainAWSEC2/assets/64348307/82da7045-54fa-4bf7-bcf0-7e9143c3f725">

2.Create an interation loop to get Instance ID,Instance Type & Launch Time.

<img width="757" alt="image" src="https://github.com/aakkat/OpenAILangchainAWSEC2/assets/64348307/b2663b10-5bc8-4039-96b4-99349a9c6f68">

3. Create an iteration of instances to get below detail of summary data
   <img width="770" alt="image" src="https://github.com/aakkat/OpenAILangchainAWSEC2/assets/64348307/381bd07b-3ee1-41a6-a8a2-0ed5ab173c66">

<img width="782" alt="image" src="https://github.com/aakkat/OpenAILangchainAWSEC2/assets/64348307/8a3b2c75-e922-44e3-a544-62fb74ebbebb">

4. Based on this we can extract summary using openai and engine used as text-davinci-003.
<img width="752" alt="image" src="https://github.com/aakkat/OpenAILangchainAWSEC2/assets/64348307/30507ef5-37f7-4d25-b806-e7d4ac4702a3">

5. Finally we can see summary detail of EC2 instance using OpenAI.   
<img width="764" alt="image" src="https://github.com/aakkat/OpenAILangchainAWSEC2/assets/64348307/2e9c3b36-9fdd-436e-929d-fc40913af50d">

