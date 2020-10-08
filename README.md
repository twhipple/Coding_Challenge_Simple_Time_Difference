# Code Challenge: 

!["Picture"]()


## Coding_Challenge_Simple_Time_Difference

This Repo is about another coding challenge that relates to a list of time differences. This is another Kata found in CodeWars and is a level 6 kyu.

In this Kata, you are given a series of times at which an alarm goes off. The task will be to determine the maximum time interval between alarms. Each alarm starts ringing at the beginning of the corresponding minute and rings for exactly one minute. The times in the array are not in chronological order. Ignore duplicate times, if any. Also, it is important to note that you need to check the time difference from the last alarme of the day to the first alarm of the morning - essential, the overnight time difference (which I didn't think about until much later).


## Examples:

### 1
solve(["14:51"]) = "23:59". If the alarm goes off now, it will not go off for another 23 hours and 59 minutes.

### 2
solve(["23:00","04:22","18:05","06:24"]) == "11:40". The max interval that the alarm will not go off is 11 hours and 40 minutes. 

### 3
This is an example I made up in order to help me solve an issue!
solve(["00:00",'02:00',"03:00","04:00",'05:00',"06:00","07:00",'08:00',"09:00","10:00",'11:00','12:00',
      "13:00","14:00",'15:00',"16:00","17:00",'18:00',"19:00","20:00",'21:00',"22:00","23:00"]) == "01:59"
      

## Additionally

This is a grea kata for understanding timedelta timedelta's - even though I solved it without importing this method.

This kata was written by: KenKamau

Thank you to Codewars for helping me practice my Python skills.

![]()