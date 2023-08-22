
# Questions

1.What is reverse-i-search in a Linux terminal?

Ans-> Many Linux terminals (and other Unix-like systems) provide a capability called reverse-i-search, sometimes known as "reverse incremental search," that enables you to search through your command history for previously entered commands. Without having to manually navigate through your command history, it's a practical approach to quickly find and rerun a command.


Start typing the characters you recall from the command you wish to find after hitting Ctrl+R. The terminal will look through its command history to find the most recent command that matches the letters you've entered so far, and it will then show it.



Continue Searching: If the command that was presented wasn't what you were looking for, you can keep typing characters, and the terminal will adjust its search based on what you've entered.



Accept a Match: When the command you wish to reuse appears, hit Enter to run it or the right arrow key to make changes

2.How do you list out the hidden directories using Linux command line tool?

Ans-> In Linux, hidden directories and files are those that start with a dot (.) as their filename. You can list hidden directories using the command line tool ls with the -a (or --all) option, which shows all files and directories, including hidden ones.

ls -a

If you want to list only hidden directories (excluding regular hidden files), you can use tools like find or grep in combination with ls. For example:

Using find: find . -type d -name '.*'

This command will search for directories (not files) whose names start with a dot (.), starting from the current directory (.).

Using grep:ls -a | grep '^\.'

3. How comfortable are you with using Linux-based OS like Ubuntu, Centos, etc?

Ans-> "Linux-based operating systems like Ubuntu and CentOS are easy for me to use. I have used these systems a lot during my college and professional career. For activities like system administration, software installation, and troubleshooting, I am skilled at using the command line. I have knowledge of numerous Linux distributions and have configured and managed servers running these operating systems. I also have experience with automation and shell scripting, which are important abilities for effective system management. In general, I have faith in my capacity to function well in Linux-based OS environments.

4.Have you ever used Servers to host any web applications in the past? If yes, what
services did you set up (Like- Apache/Nginx/FTP/SMTP, etc)?

Ans-> Yes, I have set up and configured servers to host web applications. Previously, I largely utilized Apache HTTP Server for site hosting. I have set up SSL certificates for secure connections, established virtual hosts, and enhanced server performance for faster response times.

I've worked with SMTP (Simple Mail Transfer Protocol) servers in addition to web hosting to provide email capabilities in online applications. In order to ensure appropriate email delivery and manage spam filters, I have set up and configured email servers like Postfix and Sendmail.

Overall, my server administration knowledge includes web server configuration using Apache and email services via SMTP, among other responsibilities. I am comfortable setting and maintaining these web application services.







