# ATTENTION! THE SITE IS DOWN AND WE NEED OUR SOLE AND ONLY BRILLIANT ENGINEER TO FIX THIS
<img src="https://media1.tenor.com/images/85caab51be730a4e1290cd99d7d6e085/tenor.gif">


# Issue Summary (that is often what executives will read) must contain:

Duration of the outage with start and end times (including timezone)?  
`20 seconds at 3:00:00pm -PST`
    
What was the impact (what service was down/slow? What were user experiencing? How many % of the users were affected?)?   
`100% of our 0 users lost the ability to connect to our site. Always a error 500`

What was the root cause?  
`Some intern did .phpp instead of .php`

<img src="https://i.gifer.com/2vs0.gif">



# Timeline (format bullet point, format: time - keep it short, 1 or 2 sentences) must contain:

When was the issue detected?  
`3:00:01pm -PST`

How was the issue detected (monitoring alert, an engineer noticed something, a customer complained…)?  
`Monitoring software alerted us immediately`

Actions taken (what parts of the system were investigated, what were the assumption on the root cause of the issue)?  
`Curl, top, w, history, strace. Assumed Kevin messed things up.`

Misleading investigation/debugging paths that were taken?  
`Looked into wp-config and wp-local files instead of the settings`

Which team/individuals was the incident escalated to?   
`The regional manager, Micheal Scott, and the assistant TO the regional manager, diapers Schrute`

How the incident was resolved?   
`Fixed the typo. Reboot the server`

<img src="https://media.tenor.com/images/00760d23371272db216da7919ce7c884/tenor.gif">



# Root cause and resolution must contain:

Explain in detail what was causing the issue?   
`A typo`

Explain in detail how the issue was fixed?  
`Spellcheck`


<img src="https://media1.tenor.com/images/b8401d232cca2fa7cb5e0e876de4f3cd/tenor.gif?itemid=5096483">



# Corrective and preventative measures must contain:

What are the things that can be improved/fixed (broadly speaking)?  
`Fire Kevin or use code review`

A list of tasks to address the issue (be very specific, like a TODO, example: patch Nginx server, add monitoring on server memory…)?  
`See above`

Be brief and straight to the point, between 400 to 600 words
<img src="https://i.kym-cdn.com/photos/images/original/001/050/209/b01.png">
