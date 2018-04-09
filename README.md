# ups-no-power-shutdown
A UPS with a computer connection was much, much more expensive than without, but I found a way to shut down my computer in another way with a power outage.

Just sharing an initial version of my script with a lot of debug code in it. It is a bash (Ubuntu) script, but it can also shut down Windows machines (just install Samba).

It check the ip address of my router. Just change the router IP address and if remote shutdown the shutdown script lines.

I might clean it up, but it just works and performance is not really an issue in 2018 anymore for these kind of things. I just run it every 5 minutes in my crontab.

Feel free to change the script to your own needs, but I would appreciate if you mention me as the original author.
