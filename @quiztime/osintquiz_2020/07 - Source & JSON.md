# Challenge

It's been some time since that https://osintcurio.us was launched, and somewhere in December 2018 someone posted the link to this website for the first time on a Reddit subforum. Find the forum, find the post, and then exact the timestamp of this post. If you're logged in at Reddit, you can find it in the following format:

yyyy-mm-ddThh:mm:ss+00:00

# Solution

I went to the old reddit site and used the search term "site:osintcurio.us"

![image](https://user-images.githubusercontent.com/81070073/121284916-63cb9980-c892-11eb-916e-f6fd5d0e0e53.png)

I viewed the source code and searched for the tag "datetime" to find its submitted date.

![image](https://user-images.githubusercontent.com/81070073/121284971-77770000-c892-11eb-9a44-09ea0d9977bd.png)

Flag: 2018-12-17T10:30:13+00:00
