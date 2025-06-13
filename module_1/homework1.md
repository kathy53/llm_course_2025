# HOMEWORK 1

## NOTE
I used Groq instead of GPT-4o
Also, I ran all my code locally using Docker compose

---------------------------------------
__Q1__
```$curl localhost:9200
...
"build_hash" : "42f05b9372a9a4a470db3b52817899b99a76ee73",
...
```
---------------------------------------
__Q2__
Which function do you use for adding your data to elastic?
A=index

---------------------------------------
__Q3__
What's the score for the top ranking result? (see notebook)
A=44.50

---------------------------------------
__Q4__
Return 3 results. What's the 3rd question returned by the search engine?
A=How do I copy files from a different folder into docker container’s working directory?

---------------------------------------
__Q5__
What's the length of the resulting prompt? (use the len function)
A=1446

---------------------------------------
__Q6__
Use the encode function. How many tokens does our prompt have?
A=320

---------------------------------------
# Bonus

__B1__
What's the response?

A= 
```
You can copy a file to a Docker container using the `docker cp` command. 

The basic syntax is:

`docker cp /path/to/local/file_or_directory container_id:/path/in/container`
```

---------------------------------------
__B2__
How much will it cost to run 1000 requests?

A=the total price is $0.002215


