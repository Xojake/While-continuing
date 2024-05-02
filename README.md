# While-continuing
print('Kvadrat topuvchi cheat !')
question = 'Istalgan son kiriting: '
question  += ('Agar chitimni to\'xtatmoqchi bo\'lsangiz "stop cheat" deb yozing:')
value = ''
while value != 'stop cheat':
    value = input(question)
    if value != 'stop cheat':
        print(float(value)**2)
print('The end')
