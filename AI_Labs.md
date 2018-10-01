# AI Labs

## Result
No Response

## How to apply?
LinkedIn

## What kind of interview I got?
I got on-site invitation after three days of my application on LinkedIN. However, I got no response after the on-site interview. I can't tell if there are still other interviews.

## What is the interview procedure?
There are three interviewers. I was interviewed one by one. The over all time of the interview took about 4 hours. The interview covered general data strcuture, network communication, multi-thread, white-board coding and algorithms.
### interviewer 1
At first, the interviewer asked me to introduce about myself. After that we talk about my previous project and what I have done, what is the archtecture about this. After that, the interviewer asked me to write the psudocode and data structure about LRU cache. I was a little stcuk. I wrote down the psudocode with fine functionality. However, the time complexity is worse. I took some time to modify it to constant time. The interviewer recommand me to write only the data structure and simple code next time since I was stucked by C++ data structure.
### interviewer 2
The interviewer asked me to introduce myself, too. After that, we talked about what I have done to improve the performance of my previous product. I thought we got some conflict about the performance tuning part. I declared that making data transfering to server from synchronization to asynchronization could help to reduce the network bottleneck and improve the server performance due to computing large data set, instead of one by one, indirectly. However, the interviewer thought the asynchornization has no help on the performance due to the loadin was still the same. I think both of us were right. It was just because we consider the case from differet aspect. After that, the interviewer ask me about the network communication between server and client. I got little idea about network communication since I worked on client all of my time. Then, the interviewer asked me about the authenication issue. I replied using google protobuf and GUID to recongnize the agents. To my understanding, it was not a good solution for authenication. I kept throwing my ideas for example, RSA, certificate, AES, public key and private key. However, none of them looked like a good solution to the interviewer. After that, the interviewer asked me to wrote down the mutil-thread design for file system reading and writing. I wrote down a writing thread, a reading thread and a monitoring thread. The interviewer commented that usually people wouldn't design like this but didn't show me about the correct solution. After that, the interviewer asked my to think about the archetecture about the voice recognition. The archtecture should focus on if there were many users, you should response on realtime. I tried to design the archtecture with lots of redis server in order to catch data and response quickly. However , the interviewer comments that the voice recognition could not be cached. It must compute every time. Hence, I tried to settle lots of server and used load balancing to assure that server could handle the input without delay. However, the interviewer comments that even though there is no delay, it still couldn't response in real time. At that time, I was stucked and this part was ended.
### interviewer 3
The interviewer aksed me to introduce myself, too. After that, we talked about my projects, too. The interviewer asked me some general questiones for example, "which team in this company are you intereted in?" and "Do you have any experience about AI?" After that, the interviewer asked me to write some algorithms on the whiteboard. The first question was to find the paths from a tree freom root to leaf, which that the sum of all the nodes was the target value. The second one was that we would like to find any path but not only from root to lead. You could start from any node to its child. The thrid one was that instead of from any node to its child, we would like to know any node, its adjacency and its adjacency's adjacency could be sumed to the target value. I was stucked with the question 3. The first one could be solved by recursion. The second one could be solved by recursion and tree traversal. The question 3 could be solved by dividing questions to sub questions, fro example, if target was 22, we could divide the question to find target x on the left and 22-x on the right.

## Feedback
Over all, it is not a difficult interview. Most of the quesions are general data structures and algorithms. The interviewer 1 and 3 are nice and helpful. They gave me some feedback during the interview. It would be nice if the interview 2 could give some solution or feedback for the question he asked. However, it is frustrated that there is no resonse after the interview.

## ToDo
Network Authunication
Network Communication
Read and Write Multi-Thread Desgin 

