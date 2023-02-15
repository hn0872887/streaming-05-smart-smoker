# streaming-05-smart-smoker

 Use RabbitMQ to distribute tasks to multiple workers

One process will create task messages. Multiple worker processes will share the work.

Before You Begin

Create a new repo into your GitHub. Done

Clone your repo down to your machine. Done

Upload csv file to repo. Done

Add  gitignore into your GitHub. Done


View / Command Palette - then Python: Select Interpreter Done

Select your conda environment. Done


Read the RabbitMQ Tutorial - Work Queues Done

Create bbq_producer.py file. Done

Write the code and comments in bbq_producer.py file. Done

Execute bbq_producer.py

 


Smart System
We will use Python to:

Simulate a streaming series of temperature readings from our smart smoker and two foods.
Create a producer to send these temperature readings to RabbitMQ.
Create three consumer processes, each one monitoring one of the temperature streams. 
Perform calculations to determine if a significant event has occurred.
 

Optional: Alert Notifications
Optionally, we can have our consumers send us an email or a text when a significant event occurs. 
You'll need some way to send outgoing emails. I use my main Gmail account - other options are possible. 
 
