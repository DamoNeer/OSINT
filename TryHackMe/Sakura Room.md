# Tip-Off - challenge

https://raw.githubusercontent.com/OsintDojo/public/3f178408909bc1aae7ea2f51126984a8813b0901/sakurapwnedletter.svg

What username does the attacker go by?

# Tip-Off - solution

Looking through its metadata, I found the path to file which contains the attacker's username.

![image](https://user-images.githubusercontent.com/81070073/120724464-b703ad80-c488-11eb-952d-d66a2e148bc2.png)

Answer: SakuraSnowAngelAiko

# Reconnaissance - challenge

It appears that our attacker made a fatal mistake in their operational security. They seem to have reused their username across other social media platforms as well. This should make it far easier for us to gather additional information on them by locating their other social media accounts. 

# Reconnaissance - solution

The attacker has a github page: https://github.com/sakurasnowangelaiko

On the github page, there is a PGP file. When decrypted using a tool such as https://cirw.in/gpg-decoder/, it will reveal the attacker's email address.

![image](https://user-images.githubusercontent.com/81070073/120734225-621e6200-c49d-11eb-9f6a-c9c3910e6d18.png)

![image](https://user-images.githubusercontent.com/81070073/120734306-7f533080-c49d-11eb-9ed7-16b82fc92242.png)

Doing a google search on the username will bring us to a linkedln, under the name Aiko Abe, which seems to belong to the attacker.

![image](https://user-images.githubusercontent.com/81070073/120734384-a14cb300-c49d-11eb-8923-9bf23b44e5d0.png)

What is the full email address used by the attacker? SakuraSnowAngel83@protonmail.com

What is the attacker's full real name? Aiko Abe

# Unveil - challenge

It seems the cybercriminal is aware that we are on to them. As we were investigating into their Github account we observed indicators that the account owner had already begun editing and deleting information in order to throw us off their trail. It is likely that they were removing this information because it contained some sort of data that would add to our investigation. Perhaps there is a way to retrieve the original information that they provided? 

# Unveil - solution

![image](https://user-images.githubusercontent.com/81070073/120734558-ee308980-c49d-11eb-9aec-5eeed8b8d59e.png)

The attacker has a github repository for Eth mining. There is information regarding an ethereum wallet address and the mining pool.

Here is a list of transactions associated with that address: https://ww7.etherscan.io/txs?a=0xa102397dbeebefd8cd2f73a89122fcdb53abb6ef

![image](https://user-images.githubusercontent.com/81070073/120734725-3a7bc980-c49e-11eb-8395-0ffaf04dbe31.png)

This image shows anoither cryptocurrency that the attacker has exchanged using their wallet.

What cryptocurrency does the attacker own a cryptocurrency wallet for? ethereum

What is the attacker's cryptocurrency wallet address? 0xa102397dbeeBeFD8cD2F73A89122fCdB53abB6ef

What mining pool did the attacker receive payments from on January 23, 2021 UTC? ethermine

What other cryptocurrency did the attacker exchange with using their cryptocurrency wallet? tether

# Taunt - challenge

Just as we thought, the cybercriminal is fully aware that we are gathering information about them after their attack. They were even so brazen as to message the OSINT Dojo on Twitter and taunt us for our efforts. The Twitter account which they used appears to use a different username than what we were previously tracking, maybe there is some additional information we can locate to get an idea of where they are heading to next?

We've taken a screenshot of the message sent to us by the attacker, you can view it in your browser

![](https://raw.githubusercontent.com/OsintDojo/public/main/taunt.png)

# Taunt - solution

The image shows us that the attacker's twitter handle was "AikoAbe3", but if you search it on Twitter, you will only see an empty profile with no tweets.

However, if you do a google search on "AikoAbe3", it will lead you to another profile that referenced it and that's the actual profile we are looking for: https://twitter.com/sakuraloveraiko?lang=en

![image](https://user-images.githubusercontent.com/81070073/120736587-5c2a8000-c4a1-11eb-91bf-9ede96098522.png)

These two posts are hints that we have to go to the Dark Web, specifically go to "DEEP PASTE"'s onion link and input the md5 hash to see the attacker's screenshot of Wifi and passwords. (DeepPaste has an option that let you search for screenshots after providing the md5 hash)

![vmplayer_Hqtk1kfodn](https://user-images.githubusercontent.com/81070073/120736667-854b1080-c4a1-11eb-9b04-82f16f8a5d5a.png)

The last row tells us what the home wifi's ssid is. Inputting that on https://wigle.net/search?ssid=DK1F-G will lead us to its BSSID.

What is the attacker's current Twitter handle? SakuraLoverAiko

What is the URL for the location where the attacker saved their WiFi  SSIDs and passwords? http://depastedihrn3jtw.onion/show.php?md5=0a5c6e136a98a60b8a21643ce8c15a74

What is the BSSID for the attacker's Home Wifi? 84:AF:EC:34:FC:F8

# Homebound - challenge

Based on their tweets, it appears our cybercriminal is indeed heading home as they claimed. Their Twitter account seems to have plenty of photos which should allow us to piece together their route back home. If we follow the trail of breadcrumbs they left behind, we should be able to track their movements from one location to the next back all the way to their final destination. Once we can identify their final stops, we can identify which law enforcement organization we should forward our findings to.

# Homebound - solution

First of all, the twitter post about a first class lounge is located in Haneda Airport.

![image](https://user-images.githubusercontent.com/81070073/120739346-35227d00-c4a6-11eb-834e-d4eeab934272.png)

Second of all, it took the attacker 16 hours to post that photo after taking her first flight. 

Third of all, from her linkedin profile, I see that she has gone to school and worked in Georgia, US. This would explain why the flight to Japan would take 16 hours. 

However, the white building hiding in the background of the photo is proof that she was not in Georgia. That white building is actually in Washington, DC.

I have googl'ed the best places in America to watch cherry blossoms: https://www.nationalgeographic.com/travel/article/cherry-blossom-bloom-predictions-spring

The listed places are: Washington, DC , Georgia, Connecticut...etc (There are eight places total)

Then, I cropped the white building and put in each place as keyword on Yandex to see if I was able to find an exact match.

![image](https://user-images.githubusercontent.com/81070073/120740530-381e6d00-c4a8-11eb-94a1-b9387530c9f3.png)

Bingo, Washington! The closest airport to Washington Monument is Ronald Reagan Washington National Airport.


