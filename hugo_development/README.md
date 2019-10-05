#Host
Current host is nearlyfreespeach.net
password and username are in keepass

#Create static page
just type >hugo
this will create the static files in /public and should be enough

#Manual work
For some strange reason links in index.html pointing to images work. For example src=images/portrait.jpg works fine.

But stylesheet href="css/style.css" does not work. I have not been able to figure out why

**The solution:** Place style.css in /home/public and edit index.html manually, changing css/style.css to style.css

#Upload

Upload the files via ssh with this command:

scp /home/lucius/lubob_net_website/public/ lubobde_lubobsvisitenkarte@ssh.phx.nearlyfreespeech.net:/home/public/
