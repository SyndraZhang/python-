# python-
My way to self
n = 1 
i = randon.randit(1,50)
print(i)
while n < 4 :
  guess = int(input('Enter an intrgar -->'))
  if guess > i :
    print('It is a little bigger than that.')
    n = n + 1
  elif guess < i :
    print ('It is a little lower than that.')
  else:
    print ('Congratulations!You guess it.')
    break
if guess != i :
  print ('Sorry,you dont guess it.')
  print('DO YOU WANT PLAY ONCE AGAIN?')
print('End')
