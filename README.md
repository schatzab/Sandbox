** NOTE - THIS IS NOT MY OWN WORK AND IS SIMPLY IN BETA TESTING RIGHT NOW. UPDATES FOLLOWING.

RemoteLoc App
==============

([For this DigitalOcean guide](https://www.digitalocean.com/community/tutorials/deploying-a-rails-app-on-ubuntu-14-04-with-capistrano-nginx-and-puma))

This Rails App has been fully configured with Nginx, Puma and Capistrano. This app isn't meant to be used 
as a starting point for your Application, this is just an example to take help from.


App Details
-----------

This app uses:

 - __Ruby Version:__ `2.3.0`


Test Droplet Details
--------------------

The Droplet where this App was hosted had:


 - __User:__ `deploy`
 - __App Name (For Capistrano):__ 'remoteloc'

In the DB Installation Step, I installed `MongoDB` since this app uses `Mongoid`.


Testing on Your own Droplet
---------------------------

If you'd like to test this app on your own droplet, [fork](https://github.com/sheharyarn/testapp_rails/fork)
this repo and follow the DigitalOcean Guide step-by-step replacing parameters (such as Droplet IP, SSH Port, User, etc.)
with your Repo URL and Droplet's information.


