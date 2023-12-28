**Management of remote desktop connection requests.**


As you know, as soon as an IP server goes online and Remote Desktop (Windows) is activated, thousands of robots to attack the server, start sending passwords to
connect to the server, which, in addition to the possible risks of password guessing,these efforts The interruption of the attack puts heavy pressure on the server and CPU and RAM resources
After several years of working on remote servers and seeing endless hacker attacks, I created a program to automatically block these requests by the firewall.
In general, according to the discretion of the server administrator,this has the ability to apply the necessary settings to manage the requests to enter the server


همانگونه که اطلاع دارید به محض آنلاین شدن یک آی پی سرور و فعال شدن ریموت دسکتاپ (ویندوز) هزاران هزار ربات جهت حمله به سرور ، شروع به ارسال رمز هایی برای اتصال به سرور میکنند که علاوه بر خطرات احتمالی حدس رمز عبور ، این تلاشهای بی وقفه حمله ، فشار سنگینی به سرور و منابع سی پی یو و رم وارد میکند
بعد از چندسال کار روی سرورهای راه دور و مشاهده حملات بی پایان هکرها ، یک برنامه برای قطع اتوماتیک این درخواستها توسط فایروال را ایجاد کردم
که بصورت کلی بنا به صلاح دید مدیر سرور قابلیت اعمال تنظیمات مورد نیاز برای مدیریت درخواستهای ورود به سرور را دارد


This program receives all requests to log in to Windows servers by remote desktop and makes it easier to control the connection to your server.

You can see the login requests in your Telegram bot or our suggested bot.

It is possible that your Windows Defender server will identify this file as a virus because this program will request the registration of startup in the registry if you approve it.

این امکان وجود دارد که سرور ویندوز دیفندر شما این فایل را ویروسی تشخیص دهد زیرا این برنامه در صورت تایید شما درخواست ثبت راه اندازی در رجیستری را می دهد.


To get help, type the help word into the program

The compiled program is matched with the proposed Telegram bot, and you can use the set bot to control inputs without creating a new bot in Telegram.
When starting the program, a settings.json file is created next to the program, which you can edit as you like (following the rules of the json file).
Finally, just start the 
@RDManagerBot 
https://t.me/RDManagerBot
bot in Telegram or introduce your bot to the program and set the Telegram ID code in the program.
From now on, any request to enter the server will be sent to your bot in Telegram.
