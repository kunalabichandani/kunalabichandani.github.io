---
title: How to use Instagram DM on your Mac (free, no third-party apps)
layout: post
date: 2019-07-13 22:44
image: null
category: blog
description: A quick guide on how to setup Instagram DM for Mac. Free, Easy, Safe!
---

Have you ever wanted to continue a conversation on Instagram Direct Messages but found it frustrating to pick up and unlock your phone every time? Had people sliding into your DMs when you're supposed to be 'focused' on work? 

It's unfortunate that, as of today, Instagram has no official app for Mac. Yeah, you could use the website through your browser but what's the fun in scrolling through and liking posts without messaging people? For whatever reason, Windows has a native app of its own while Mac doesn't. That said, there are a few third-party apps that exist, although I've steered away from those because I'd rather not give them access to my password, posts, usage activity, messages, and the like (pun intended). 

I've written this tutorial to show how anyone on a Mac can set up Instagram DM in 60 seconds (if you're good at following instructions), without worrying about your data or spending money.  

<div class="breaker"></div>

Requirements: Mac, internet connection.

**Launch Automator**

Do this by searching for 'Automator' on Spotlight Search (quick launch by holding *command + space*). You could also look for it in your applications - it's an icon of a robot holding a black pipe, normally in the default 'Other' folder inside the 'Applications' folder. 

**Create a new document**

Click *File > New* and in the dialog box that appears, choose 'Application' as the document type. 

**Add the "Get Specified URLs" action**

Search or scroll till you find the "Get Specified URLs" action. You can then double-click this option or drag it onto the pane on the right.

![Screenshot](/assets/images/getspecifiedurls.png)

Select the address (http://www.apple.com) that was pre-filled in the address box and remove it. Now, add Instagram's address (make sure to add http://www at the beginning): 

{% highlight html %}
http://www.instagram.com
{% endhighlight %}

**Add the "Website Pop-up" action**

As done before, find the "Website Pop-up" action and add it.

![Screenshot](/assets/images/websitepopup.png)

Choose from the options for 'Site Size'. I prefer the 'iPhone' option as it creates a small, iPhone screen-sized application window that can be dragged around, but you can also choose alternate sizes.

For **'User Agent'**, choose the **'iPhone'** option. This is important - if you choose any other option, you will not be able to use DM. 

**Save your application**

Press *command + S* or click *File > Save*. Name your application 'Instagram', and save it to your 'Applications' folder. That's all! Open your app from your Applications folder. You'll be taken to the login/signup screen; once you're logged in, you should see something like this: 

![Screenshot](/assets/images/instahomepage.png)
![Screenshot](/assets/images/instadm.png)

**Voila!** You can now continue your DM conversations right from your Mac!

NOTE: You will stay signed in to your account, so the next time you open the app, you won't need to sign in all over again.


<div class="breaker"></div>

**Bonus:** Customize the app icon for your newly created Instagram app on your Mac! 

![Screenshot](/assets/images/dock.png)

This is super easy: 
1. Find and download an Instagram logo (.pngs with transparent backgrounds work best)
2. Open the logo in Preview and hit *command + A*  followed by *command + C*
3. Open your Applications folder and select 'Instagram'. Hit *command + I* to get app info
4. Click the small robot icon on the top left corner. Hit *command + V*

Boom. You now have an official-looking Instagram app that can handle DMs on your Mac.

PS: For those of you wondering how I have Google Calendar and Keep apps on my Mac, I used Automater to make them ;)

<div class="breaker"></div>


I was  surprised this solution didn't exist already, so I did some digging. I found that Instagram only recently (mid-May) enabled DM on mobile browsers, which is exactly the trick this solution uses. It also looks like you'll soon be able to [access Instagram for web on all devices](https://techcrunch.com/2019/02/12/instagram-direct-desktop/). Yes, that would make this trick a little redundant, but I've found that being able to launch a mobile-sized application in one click is easier than using Instagram in my browser anyway. 

I hope this was useful! Feel free to reach out with any comments or questions [here](mailto:abichandani.kunal@gmail.com), I'm happy to help with issues or concerns you may have.

*A huge shoutout to Leela Jay for helping me edit this article. Please do share this with friends who own a Mac and would find this trick useful. Watch this space for more blog posts!*