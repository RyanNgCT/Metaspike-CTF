# 1 - It's About Time

## Part 1

You have received the email below in connection with a legal action. The timing of the email is critical. Examine the email and determine if it is more likely to be legitimate or fake.

Enter L for legitimate, F for fake. More to come based on your answer.


### Approach

We can first use mxtoolbox to analyse the headers after opening them in thunderbird. [The results](https://mxtoolbox.com/Public/Tools/EmailHeaders.aspx?huid=ed4f311b-4617-4f3d-a20a-2e857063375e) show that `DKIM-Signature Body Hash Not Verified`. After some exploration, I discovered this means that the computed hash does not match the `bh=` field, which suggests that the email might have been modified during transit.


---

## Part 2

Congrats on making that determination! You are now asked to take this a step further, and determine the earliest date and time the email could have been sent based on the timing information you can locate within the file.

You will be examining the same email as in Part 1.

Enter the timestamp in UTC in the following format: yyyy-mm-dd hh:mm (e.g., 2005-11-20 13:17)
