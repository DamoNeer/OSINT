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


