# Py3dns-for-windows
Py3dns Changes for Windows Usage

The credit goes to anyone who for fixing Py3dns so that it worked for windows ( not really a strong programmer so I couldn't made huge changes like other people did)

I just made a small edit of changing the self.async to self.py3async and then it worked for me

Hope this helps windows user so that they can use DNS


First Install py3dns 

Then go to C:/Users/"yourusername"/AppData/Local/Programs/Python/Python37-32/Lib

Replace the DNS folder with the folder in the repository

This should fix the FileNotFoundError: [Errno 2] No such file or directory: '/etc/resolv.conf' problem

Thats how i fixed my problem for Windows 10 
