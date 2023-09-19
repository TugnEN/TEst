Question_1 = 'Какая версия языка сейчас актуальна?'
Answer_1 = 'Python 3'.lower().upper().title()
while True:
    user_answer = input('Введите свой ответ №1 на вопрос {0}: '.format(Question_1))
    if user_answer == Answer_1:
       print('Ответ верный!')
       break

    else:
       print('Ты ошибаешься.')


Question_2 = 'Сколько значений имеет bool?'
Answer_2 = '2'
while True:
    user_answer = input('Введите свой ответ №2 на вопрос {0}: '.format(Question_2))
    if user_answer == Answer_2:
        print('Ответ верный!')
        break

    else:
        print('Ты ошибаешься.')


Question_3 = 'Какая кодировка используется в строках?'
Answer_3 = 'UFT8'
while True:
    user_answer = input('Введите свой ответ №3 на вопрос {0}: '.format(Question_3))
    if user_answer == Answer_3:
        print('Ответ верный!')
        break

    else:
        print('Ты ошибаешься.')


Question_4 = 'Что можно делать со строками?'
Answer_4 = 'Складывать'
Answer_41 = 'Склеивать'
while True:
    user_answer = input('Введите свой ответ №4 на вопрос {0}: '.format(Question_4))
    if user_answer == Answer_4:
        print('Ответ верный!')
    if user_answer == Answer_41:
        print('Ответ верный!')
        break

    else:
        print('Ты ошибаешься.')


Question_5 = 'Чего нельзя делать со строками?'
Answer_5  = 'Забывать документацию'
Answer_51 = 'Забывать их документацию'
while True:
   user_answer = input('Введите свой ответ №5 на вопрос {0}:'.format(Question_5))
   if user_answer == Answer_5:
       print('Ответ верный!')
   if user_answer == Answer_51:
       print('Ответ верный!')
       break

   else:
       print('Ты ошибаешься.')


Question_6 = 'Как хранится память внутри ПК?'
Answer_6  = 'Числами'
while True:
   user_answer = input('Введите свой ответ №6 на вопрос {0}:'.format(Question_6))
   if user_answer == Answer_6:
       print('Ответ верный!')
       break

   else:
       print('Ты ошибаешься.')



Question_7 = 'Сколько байтов в одном бите?'
Answer_7  = '8'
while True:
   user_answer = input('Введите свой ответ №7 на вопрос {0}:'.format(Question_7))
   if user_answer == Answer_7:
       print('Ответ верный!')
       break

   else:
       print('Ты ошибаешься.')



Question_8 = 'Как предстовляют строки собой в различных кодировках?'
Answer_8 = 'Байты'
while True:
    user_answer = input('Введите свой ответ №8 на вопрос {0}:'.format(Question_8))
    if user_answer == Answer_8:
        print('Ответ верный!')
        break

    else:
        print('Ты ошибаешься.')


Question_9 = 'Что должно иметь тело условия?'
Answer_9 = '4 пробела'
while True:
    user_answer = input('Введите свой ответ №9 на вопрос {0}:'.format(Question_9))
    if user_answer == Answer_9:
        print('Ответ верный!')
        break

    else:
        print('Ты ошибаешься.')


Question_10 = 'Что может бытьв правой части for?'
Answer_10 = 'Только итерабельные объекты'
while True:
    user_answer = input('Введите свой ответ №10 на вопрос {0}:'.format(Question_10))
    if user_answer == Answer_10:
        print('Ответ верный!')
        exit()

    else:
        print('Ты ошибаешься.')
