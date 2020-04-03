# python-house
buying house

print()
print()
print('   Ziyotek bank is looking for home buyers')
print(' with clean background and good credit score')
print()
print()



home = input('How much is your house costs? : ')
good_report = int(home) / 10
bad_report = int(home) / 5
score = input('what is your credit score? :')
print()
print('        please type "yes" or "no"')
criminal_report = input('do you have any criminal records? :')
print()
print()




good_credit = True
bad_credit = False
if good_credit and int((criminal_report) == 'no') and 640 >= int(score) <= 800:
    print('           CONGRATULATIONS!!!')
    print('           You are approved!!')
    print('credit score is ' + score)
    print('good credit score and no criminal reports')
    print('you need to put down 10%')
    print('which is $' + str(good_report))
elif bad_credit or int((criminal_report) == 'yes') or 500 <= int(score) < 640:
    print('           CONGRATULATIONS!!!')
    print('           You are approved!!')
    print('Your credit score is ' + score)
    print('Bad credit report but we are trusting you')
    print('You will need to put down 20%')
    print('which is $' + str(bad_report))


else:
    print('Buyers required with good credit report')
