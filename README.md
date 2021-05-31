# pr0xy_meth0de
Add data into burp proxy






im Happy to say this you dont need to install any third party service to run my tool 😃
its pure Python ❤️️

Steps to install :




1. mkdir ~/gadgets
2. cd ~/gadgets/
3. git clone https://github.com/blackdaliyadali/pr0xy_meth0de.git
4. cd pr0xy_meth0de 
5. chmod +x *
6. chmod +x install.sh
7. Now Open burp 
8. Got to proxy and select option
9. Now click add 
10. use this proxy host = 127.0.0.1 port = 7777

# Syntax :

# For Single Domain or url 
      python pr0xy_meth0de.py -p http://yourserver.com/
       
# For multiple domain or Url 
      cat live-domain.txt | xargs -n1 -p50 python pr0xy_meth0de.py --parse
      
# Happy hacking 💀
# Jai Hind 🇮🇳
