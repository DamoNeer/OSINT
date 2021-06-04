# Story - challenge

Background Information:

You are Aleks Juulut, a private eye based out of Greenland. You don't usually work digitally, but have recently discovered OSINT techniques to make that aspect of your job much easier. You were recently hired by a mysterious person under the moniker "H" to investigate a suspected cheater, named Thomas Straussman. 

After a brief phone-call with his wife, Francesca Hodgerint, you've learned that he's been acting suspicious lately, but she isn't sure exactly what he could be doing wrong. She wants you to investigate him and report back anything you find. Unfortunately, you're out of the country on a family emergency and cannot get back to Greenland to meet the deadline of the investigation, so you're going to have to do all of it digitally. Good luck!

# Story - solution

Who hired you? ks{H}
Who are you investigating? ks{thomas straussman}

# Let's get started!! - challenge

How exciting! Through talking to people who know Thomas, you've found out that he has a very guessable online handle: tstraussman. With this handle, we can find his social media accounts, and start off this room.

# Let's get started!! - solution

![image](https://user-images.githubusercontent.com/81070073/120871158-bf72eb80-c54f-11eb-8d2b-0b5f0b8bfe15.png)

- Buddha in the background
- He seems to like Christmas according to his bio

![image](https://user-images.githubusercontent.com/81070073/120871233-ecbf9980-c54f-11eb-9983-6997fffbed4c.png)

He posted a meme on Reddit on his birthday to celebrate his 30th birthday.

![image](https://user-images.githubusercontent.com/81070073/120871258-fc3ee280-c54f-11eb-8ef2-c48f6350e1bd.png)

A reply from his fiance which shows her twitter handle.

What is Thomas' favorite holiday? ks{Christmas}

What is Thomas' birth date? ks{12-20-1990}

What is Thomas' finacee's Twitter handle? ks {fhodgelink}

What is Thomas' background picture of? ks{Buddha}

# Spider... what? - challenge

User Spiderfoot to perform scans on "Thomas Straussman" and "Tstraussman".

# Spider... what? - solution

I did a scan on the target "Tstraussman" and I got the following results.

![image](https://user-images.githubusercontent.com/81070073/120871740-5b512700-c551-11eb-80fd-e258f92b6dde.png)

Navigating to the shadowban API link, I was able to see the value of "search".

![image](https://user-images.githubusercontent.com/81070073/120871719-4e343800-c551-11eb-9ca9-aa021cbf30fb.png)

What was the source module used to find these accounts? sfp_accounts

Check the shadowban API. What is the value of "search"? ks{1346173539712380929}

# Connections, connections.. - challenge

Since you have gotten most useful information from Thomas' Twitter, it's time to "pivot" to his fiancee's account.

What personal information can you find?

# Connections, connections.. - solution

![image](https://user-images.githubusercontent.com/81070073/120871787-8b98c580-c551-11eb-987b-3375f89f3cec.png)

First two tweets show a TV show that she is currently watching and her adorable cat's name.

![image](https://user-images.githubusercontent.com/81070073/120871829-a4a17680-c551-11eb-8928-7d81057037dd.png)

The next two posts tell us that her mother's birthday is on the 25th December and she went to Germany for vacation. Since the question is asking for the city as well, I did a reverse image search on the image. On Bing, I was able to confirm the city and the country.

![image](https://user-images.githubusercontent.com/81070073/120871921-f34f1080-c551-11eb-9689-4f7de764f2b5.png)

Where did Thomas and his finacee vacation to? Koblenz, Germany

When is Francesca's Mother's birthday? December 25th

What is the name of their cat? Gotank

What show does Francesca like to watch? 90 Day Fiancee

# Turn back the clock!! - challenge

Use the old version of Reddit and wayback machine to find deleted contents.

# Turn back the clock!! - solution

![image](https://user-images.githubusercontent.com/81070073/120872167-bafc0200-c552-11eb-914a-0396316e2035.png)

I found that in December 2020 there was a deleted comment on the same birthday post on Thomas' profile I mentioned earlier. The comment was made by someone named Hans with the handle "minikhans".

I did a scan on "minikhans" using SpiderFoot and I potentially found his first name and last name from his gravatar profile's json file.

![image](https://user-images.githubusercontent.com/81070073/120872286-18904e80-c553-11eb-8a8f-ed8ba9230a1f.png)

Hans made a post celebrating the fact that he got a job from his friend Thomas. Assuming that the job is local, he and Thomas might be living in the same city. Thomas' twitter profile said that he lives in Nuuk, Greenland.

![image](https://user-images.githubusercontent.com/81070073/120872367-6d33c980-c553-11eb-890d-230c0608a1cc.png)

Furthermore, Hans' reddit bio said "Nuuk is the best"

![image](https://user-images.githubusercontent.com/81070073/120872410-905e7900-c553-11eb-9ef9-4f9e23fb967f.png)





