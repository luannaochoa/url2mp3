#url2mp3

##The script can be used globally with this command  
``cp url2mp3 /usr/local/bin`` 

##Create an alias to cd and play the music 

Create the .bash_profile or edit the existing profile 
``nano .bash_profile``

Add the alias to the file 
``alias md='cd /Users/luannaochoa/Music && play *mp3'``

Refresh the bash environment with the following
``source ~/.bash_profile``

Test your command
``md``