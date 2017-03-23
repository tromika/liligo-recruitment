# 2017

So we're interested how you can solve a minor task in your preferred programming language.
You have x minutes to complete this task.

As we've shared, you have to use Docker and Kafka. I hope you are now quite familiar with Docker.

I've attached a docker compose file which builds the test environment for you (Kafka + producer). So just download the file and hit docker-compose up -d in the console where the file is located.


Your task will be to consume the messages from a topic named test and calculate and expose the average for the numbers what're coming from the stream at every 10 seconds. You'll get JSON data in the following format e.g.: {'number': 0.1312321}

This task is general on purpose to give you many ways to solve it. Whatever your method is the goal is to get the average of numbers consumed in the last 10 seconds. So basically the output is one number in every 10 seconds. The way how you present the averages depends on you, so could be printed to console, file, log etc.

The Kafka environment is available at localhost:9092 that used to be the default for most of the consumer clients.

I'd ask you to create a public repo on a revision control and source code tracking service (preferably Github, Gitlab or BitBucket). I'd also kindly ask you please don't share the docker-compose.yml file when uploading your solution. As a submission please send to us your repo's location even if you don't finish the task completely. So don't forget to commit and push your solution at the end!

Also please give some instructions how we can run your project so write a minimal documentation in few words as a readme file.
