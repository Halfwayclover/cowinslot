# cowinslot
Enter your pincode and get slot availability for your pincode 24/7. It even pings you when someone else cancels thier appointment i.e a single or few slots are available

This program will ping you approximately once every 4-5 seconds or till the availability drops to 0

It will always check for 2 days i.e today and tommorow ( you can change this on by changing d3 to d1 for today and d2 for tommorow on line 72).

You need to use jupyternotebook or somekind of local host to run this program as it need to connect to the internet to make api calls.    
By default it will show both paid and non paid but only send notification for the free slot's on your telegram if you set it according to the instructions below:

#unhash line - 10,60,61,62,90,91,92,96,97,98 and enter your telegram bot send message link with text={0} at end, if you want to get updates on telegram
#example telegram='https://api.telegram.org/bot1111111111:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx-xxxx/sendMessage?chat_id=1111111111&text={0}'

