# dvla - challenge

![carreg](https://user-images.githubusercontent.com/81070073/120700727-d984cf00-c466-11eb-8081-30cadac51b90.PNG)

We've managed to snag a picture of the front of a new Person of Interest's car. We need you to find out the make of the car and the month it was made in!

We've attached the photo from a local CCTV camera, take a look?

Enter as such: (Brand)(SPACE)(Month)

# dvla - solution

The title of the challenge is refers to "Driver and Vehicle Licensing Agency" in the UK.

![image](https://user-images.githubusercontent.com/81070073/120699747-a857cf00-c465-11eb-9949-5bbf86f7aa37.png)

Answer: ford june

# connectionrefused - challenge

We're trying to access this web address: http://time-traveler.icec.tf/

The server is not responding! It is essential that we find the information contained on this site as we suspect it to be part of a criminal enterprise.

Sources suggest that the site was accessible about 4 years ago, not sure how that is relevant but it might mean something to you?

(Please enter the line of text in the box below, when you find it...)

# connectionrefused - solution

Enter the url in https://archive.org/web/ and navigate to snapshots 4 years ago (2016)

![image](https://user-images.githubusercontent.com/81070073/120700042-02f12b00-c466-11eb-83e2-e849573876ef.png)

Answer: IceCTF{Th3y'11_n3v4r_f1|\|d_m4h_fl3g_1n_th3_p45t}

# chemtrails - challenge

Find the seat number

![image](https://user-images.githubusercontent.com/81070073/120700649-c3770e80-c466-11eb-96b4-7a515d9295a7.png)

# chemtrails - solution

Use an online barcode reader to get information about the flight: https://online-barcode-reader.inliteresearch.com/

![image](https://user-images.githubusercontent.com/81070073/120700834-01743280-c467-11eb-9bce-bb197d130662.png)

Answer: 22B

# bigbrother - challenge

Find the country

Live camera feed: http://81.82.201.132

# bigbrother - solution

I looked up the location of the ip address and I found out which country it's located in.

Answer: Belgium

# balancethebooks - challenge

Given its confirmation statement made on 31 Dec 2019, find how much cash is held by the company "TECHNOLOGY SERVICES LIMITED".

Gives answer in thousands.

# balancethebooks - solution

https://find-and-update.company-information.service.gov.uk/company/01867162/filing-history

The first link I clicked after using the key phrase "technology services limited company number lookup" led me to the publicly available financial statements and one of which is a balance sheet made on 31 March 2019 that states how much cash the company holds at that time.

https://find-and-update.company-information.service.gov.uk/company/01867162/filing-history/MzI1Mjc3OTE3NGFkaXF6a2N4/document?format=pdf&download=0

Answer: 102.347

# readyfortakeoff - challenge

Please find the TIME OF ARRIVAL AT DESTINATION of that first flight, so that we can place officers to arrest them.

Once again we have very little to go on, aside from what I think is a camera feed.

LIVE CAMERA FEED: http://87.54.59.228

![camfeed-3](https://user-images.githubusercontent.com/81070073/120705045-2919c980-c46c-11eb-825d-e5a505d8dd3b.JPG)

# readyfortakeoff - solution

This challenge was weird and possibly it's because I am doing this challenge a year later.

The camera feed shows me that the departing airport is going to be Bornholm Airport in Denmark. 

I looked up its daily flight schedule and I noticed that the first flight tends to be DX31 which departs at 6:20am and arrives at Copenhagen at 7:00am. I have also made sure to look at the same day of the week which is a Wednesday according to the camera feed.

However, 7:00am is not the answer. 7:20am is the correct answer after a few tries using 7:00am as a baseline.

Answer: 07:20

# inplainsight - challenge

Please tell us what the HIDDEN MESSAGE within the specimen image provided is.

Stegosaurus: https://mystegosaurus.co.uk/

![specimen-image](https://user-images.githubusercontent.com/81070073/120705282-7bf38100-c46c-11eb-99c7-db51eb9da7a6.png)

# inplainsight - solution

This one was surprisingly straightforward. I just uploaded the image on the given steganography website and decoded it without giving a passphrase.

Answer: Meet me at London Heathrow Airport at the usual time where we will begin executing our plan.

# gunpowder - challenge

Could you please find the NAME OF THE ROAD that runs outside the building this camera is in.

![camfeed-2](https://user-images.githubusercontent.com/81070073/120705604-e1e00880-c46c-11eb-8a9a-348099fbcf3a.PNG)

# gunpowder - solution

Simply googling "the birchmount lofts location" will lead me to the address according to the third link on the page:
"1555 birchmount rd"

![image](https://user-images.githubusercontent.com/81070073/120705824-24094a00-c46d-11eb-8bee-71b067a48086.png)

Answer: birchmount

# rollingeyes - challenge

So we can be confident we've actually spotted them, can you confirm the COLOUR of their HOODIE and the COLOUR of their T-SHIRT.

All they've given me is an overlay from the drone... Hopefully this is enough? I've attached it to this tasking for you. We think they were getting out of a car at the time.

Enter the flag as such: (HOODIE COLOUR) (SPACE) (T-SHIRT COLOUR)

![drone-1](https://user-images.githubusercontent.com/81070073/120705967-54e97f00-c46d-11eb-86d5-104c017e261b.JPG)

# rollingeyes - solution

I went to google map and searched for "Poppy-n-Pals Pet Care Service" for the general location.

Once I have found the general location, I planned to look at the street view from bottom right corner counterclockwise from outer street to inner street. Within minutes of clicking through street view, I have found the target on Amherst Cres.

I have also made sure to look at the most recent view on street view due to the nature of when this CTF was created.

![image](https://user-images.githubusercontent.com/81070073/120707644-72b7e380-c46f-11eb-9458-8bd24b9a207d.png)

Answer: red blue

# proofinthesignal - challenge

We've received fresh intel from the team leading an important investigation.

We've become aware that one of our targets, James Markson, has retained his links with the city of Bristol, UK.

We've also learned that this individual always has his personal hotspot enabled on his smartphone, as he does not wish to subscribe to a regular home broadband service.

This means the target's WiFi signal from their phone may have registered on a public WiFi mapping service.

One intelligence analyst noted that 'jammy' may be the SSID (the name of the wireless network).

The team says you'll need a sharp eye for this one.

What is the STREET NAME where we the target has likely been in the city of Bristol?

# proofinthesignal - solution

There is only one result that comes up on https://www.wigle.net after inputting city as "Bristol" and SSID as "jammy".

![image](https://user-images.githubusercontent.com/81070073/120710678-4a31e880-c473-11eb-8cd1-90e326c0b3a7.png)

The street address of the coordinates is: st marks rd

Answer: st marks road

# sos - challenge

--. --- .-.. -.. . -. . .- --. .-.. .

# sos - solution

This is morse code.

Answer: GOLDENEAGLE

# undercover - challenge

It seems like there's nothing there, but why would a target have a blank file on their computer? Are they hiding something?

We really need to find the lock combination for the self-storage unit where the target has stashed counterfeit bank notes. We've trawled through all the other files we've found already, and its just this one that remains.

Have a look for us would you?

# undercover - solution

Press "Ctrl + A" to select all in the pdf, copy and paste the content somewhere to see the text.

![image](https://user-images.githubusercontent.com/81070073/120712394-6c2c6a80-c475-11eb-9ad8-0b6ddcf2636e.png)

Answer: 956445

# defrauded - challenge

Can you have a look at the attached fraudulent invoice and find out the ORIGINAL DATE OF CREATION by the legitimate TP and Co?

Enter your response as: DD/MM/YYYY.

# defrauded - solution

![image](https://user-images.githubusercontent.com/81070073/120712621-b9a8d780-c475-11eb-9957-5ae9445c4b63.png)

Answer: 13/05/2012

![DCIM453](https://user-images.githubusercontent.com/81070073/120712754-e5c45880-c475-11eb-80de-785d32c0c81e.jpg)

# photophile - challenge

What is the CAMERA MODEL / DEVICE MODEL of the device used to photograph the poppies?

![DCIM453](https://user-images.githubusercontent.com/81070073/120713086-4a7fb300-c476-11eb-8145-50bc1e08b964.jpg)

# photophile - solution

I used "Jeffrey's Image Metadata Viewer" to look at the exif data of the photo.

![image](https://user-images.githubusercontent.com/81070073/120713078-481d5900-c476-11eb-81b7-4a9b49966aa3.png)

Answer: Moto G3

# xorelse - challenge

QeOhnsr{KuZu)(

Enter the WiFi password as the flag.

# xorelse - solution

I tried to bruteforce with Cyberchef and that didn't seem to work. I found another tool that will bruteforce for me:
https://scwf.dima.ninja/#

![image](https://user-images.githubusercontent.com/81070073/120714122-a4cd4380-c477-11eb-972b-a78382e88aa9.png)

# mothertongue - challenge

I copied the text from pastebin to my notepad and I found a string that is different from the rest.

We can't make sense of it, find whatever is lurking in there? It could be big or small. It could be meaningful or meaningless. But its there.

LINGUIST'S EXTRACT: https://pastebin.com/mkQYkMk9

![image](https://user-images.githubusercontent.com/81070073/120715444-73557780-c479-11eb-849b-0cba16332840.png)

Answer: clouds

# hostiletakeover - challenge

We know there is publicly searchable data made available by the Land Registry which could help us with what we're after.

Can you find out the BUSINESS NAME of the previous owner of the property that can be inferred from the seized bank statement?

![image](https://user-images.githubusercontent.com/81070073/120716529-07740e80-c47b-11eb-8cbf-c0fbc7558838.png)

# hostiletakeover - solution

Navigating to Land Registry and clicking "Search house prices" will lead you to this site: https://landregistry.data.gov.uk/app/ppd

I set both min and max price to be 425000000 and date ranges from 2019-08-02 to 2019-10-02.

![image](https://user-images.githubusercontent.com/81070073/120717022-ba446c80-c47b-11eb-9f8d-06535efd4658.png)

Answer: Tesco

# bitcoinbuster - challenge

Based on the 3.581074451254057 BTC figure being obtained on 1st Feb 2020 from the Market Open price alone, which COUNTRY is the ransomware creator most likely to be from?

# bitcoinbuster - solution

I need to calculate the product of the bitcoin open price for that currency on 1st Feb 2020 and the bitcoin transaction amount for each currency.

I wrote a script that would iterate each currency, parse the open price of BTC on that day from Yahoo Finance for that currency, calculate the product, and print out the results.

```

import re
import requests
from bs4 import BeautifulSoup


def location_checker(currency):
    BTC_amount = 3.581074451254057
    epoch = str(1580515200)  # February 1, 2020 12:00 AM
    url = 'https://finance.yahoo.com/quote/BTC-'+currency + \
        '/history?period1='+epoch+'&period2='+epoch + \
        '&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true'
    soup = str(BeautifulSoup((requests.get(url)).text))
    Regex_Pattern_open = r'(?<=data-reactid="55">)[\d,.]+'
    product = "{:.2f}".format(float(
        ((re.search(Regex_Pattern_open, soup)).group().replace(',', ''))) * BTC_amount)
    print(currency + ": " + product)


currency_list = ['USD', 'EUR', 'CAD', 'GBP',
                 'INR', 'KRW', 'AUD', 'CNY', 'JPY', 'RUB']

for currency in currency_list:
    location_checker(currency)
----------------------------------------------------------------------------------------------
USD: 33470.01
EUR: 30166.47
CAD: 44306.23
GBP: 25347.24
INR: 2393071.80
KRW: 40029117.72
AUD: 50000.00            #This seems to be the one.
CNY: 232171.37
JPY: 3627980.04
RUB: 2141243.49

```

Answer: Australia
