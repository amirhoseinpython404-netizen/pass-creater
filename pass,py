import random
path ="C:/Users/known/Desktop/PasswordTxt"
f=open(path,"a")
l_w = "abcdefghijklmnopqrstuvwxyz"
u_w = l_w.upper()
n = "0123456789"
s = "!@#$%^&*(){}[]_"
ch = l_w + u_w + n + s

password = "".join(random.sample(ch, 15))

for i in range(101):
    f.write( "".join(random.sample(ch,15)) +"\n" )

