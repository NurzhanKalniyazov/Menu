# Menu
with open('asd1.txt','w') as fout:
    print("Cook Juice Kazy Apple",file=fout)
import time
a=time.strftime('%H')
print(a)
if ('7'<str(a)<='10'):
    print('Breakfast:')
    with open("asd1.txt","r") as source:
             text=source.read()
             textA=text.split(' ')
             import random
             a1=random.choice(textA)
             with open('qwe.txt','w') as fout1:
                 fout1.write(a1)
                 with open('qwe.txt','r') as fin:
                     c=fin.read()
                     if len(set(a1)-set(c))!=0:
                         print(a1)
elif ('10'<str(a)<='15'):
    print('Lunch:')
    with open("asd1.txt","r") as source:
             text=source.read()
             textA=text.split(' ')
             import random
             a1=random.choice(textA)
             with open('qwe.txt','w') as fout1:
                 fout1.write(a1)
                 with open('qwe.txt','r') as fin:
                     c=fin.read()
                     if len(set(a1)-set(c))!=0:
                         print(a1)
elif ('15'<str(a)<='24'):
    print('Dinner')
    with open("asd1.txt","r") as source:
             text=source.read()
             textA=text.split(' ')
             test=[]
             import random
             a1=random.choice(textA)
             test.append(a1)
             for i in range(0,len(test)):
                     if len(set(a1)-set(test[i]))!=0:
                         print(a1)
