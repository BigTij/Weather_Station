# Weather_Station

Here is a little project where i use 2 raspberry pi to read %RH and temperature in my greenhouse, 
and print the data in a nice looking website on local host. 

I used a LAMP server on my 2nd pi in order to store all the readings in a database so that i can
print the last 24h of readings on a graph. 

################################################################################################
#                              For new mysql users:                                            #
################################################################################################

make sure to write your configurations in the right file since apparently in the version of mysql
i used, they kept the old mysql file structure even if they switched to the mariadb config files.
It took me a while to realise i was using the wrong file.


By: Jonathan Lussier, April 11th 2020
