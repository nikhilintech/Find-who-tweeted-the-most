Problem: Find who tweeted the most!

You will be given a list of tweets
Your program should find the user who has tweeted the most


Input format:
1. Read the input from console.
2. First line of input should be number of test cases
3. Remaining lines of input should contain each test case input. 


For each test case input:
1. First line should contain number of tweets.
2. Followed by N lines, each containing user name and tweet id separated by a space.


Output format:
Find the user with max number of tweets. Print user name and total number of tweets.

If multiple users are having same number of tweets, then print all the users in alphabetical order of user names.

Sample 1:
Input 
1
4
sachin tweet_id_1
sehwag tweet_id_2
sachin tweet_id_3
sachin tweet_id_4

Output:
sachin 3


Sample 2:
Input 
1
6
sachin tweet_id_1
sehwag tweet_id_2
sachin tweet_id_3
sehwag tweet_id_4
kohli tweet_id_5
kohli tweet_id_6

Output:
kohli 2
sachin 2
sehwag 2


Sample 3:
Input 
2
4
sachin tweet_id_1
sehwag tweet_id_2
sachin tweet_id_3
sehwag tweet_id_4
5
dhoni tweet_id_10
dhoni tweet_id_11
kohli tweet_id_12
dhoni tweet_id_13
dhoni tweet_id_14


Output:
sachin 2
Sehwag 2
dhoni 4
