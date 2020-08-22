# homeStorage-NAS
Network attached storage on a raspberry pi and an external hard drive <br>
Use a raspberry pi to accept and store files through a web server <br>
This is done with a simple apache server hosted on the raspi<br>
Access the server using the ipv4 adress of your raspberry pi (run command <code>ifconfig</code>)<br>
Find your files by going to <code><i>ip/uploads</i></code> for example <code>192.168.1.67/uploads<br></code><br>
<b>Change these</b><br>
You can change the allowed file types by changing the <code>$allowed = array('txt', 'jpg', 'png');</code> and adding different file types<br>
You can change the file end destination by changing the <code>$f_destination = '/var/www/html/uploads/' . $f_name_new;</code>

<b>This is a bad implementation but its easy to integrate with samba and have it working much better</b>
