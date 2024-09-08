# love calculator
 It calculates the love percentage between the two persons
 name1=input('enter your name:')
name2=input('enter him/her name:')
name=name1+name2
name=name.lower()
t=name.count('t')
u=name.count('u')
r=name.count('r')
e=name.count('e')
true=t+r+u+e
l=name.count('l')
o=name.count('o')
v=name.count('v')
e=name.count('e')
love=l+o+v+e
love_calculator=int(str(true)+str(love))
print(love_calculator)
if love_calculator<10 or love_calculator>90:
    print(f"your score is{love_calculator} and you like coke and mentos")
elif love_calculator>=40 and love_calculator<=50:
    print(f"your score is{love_calculator} and your are alright together")
else:
    print(f"your score is{love_calculator}")

