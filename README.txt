COMP30850 Assignment 2
----------------------------------

This dataset consists of three files related to a specific Twitter list:

1. list_members.jsonl: A JSON Lines (JSONL) file, where each line in the file is a separate JSON document. Each JSON document contains the Twitter user profile of a list member.
2. followers.csv: A tab-separated text file, indicating the friend/follower relations between pairs of list members. The first two columns contain a pair of ordered screen names X and Y, indicating that user X follows user Y. The third column indicates the date on which X started following Y.
3. tweets.jsonl: A JSON Lines (JSONL) file, where each line in the file is a separate JSON document. Each JSON document represents a tweet posted by one of the list members. 


Related links:

- Details on the JSONL format:
http://jsonlines.org

- Details on the Twitter JSON format for user profiles:
https://developer.twitter.com/en/docs/twitter-api/v1/data-dictionary/object-model/user

- Details on the Twitter JSON format for tweets:
https://developer.twitter.com/en/docs/twitter-api/v1/data-dictionary/object-model/tweet
