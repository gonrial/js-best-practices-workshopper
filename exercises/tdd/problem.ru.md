# Разработка через тестирование (Test-Driven Development, TDD)

Это упражнение проверит ваше умение писать код, основанный на предоставленных тестах. Используя разработку через тестирование, вы пишете тесты для функциональности, которую хотите реализовать в первую очередь. Затем вы пишете код для метода, тесты для которого вы уже написали.

В этом упражнении тесты уже готовы, но они будут проверять функционал метода который вы создадите, convertToChange(). convertToChange() принимает в качестве аргумента одно целое число в центах (так, $0.89 = 89) и возвращает массив монет, которые в сумме дадут это число. Обратите внимание на то, что массив должен содержать монеты наибольшего номинала. Например, если мы передаём 26, вы должны вернуть ['p', 'q'] (1 penny и 1 quarter), даже если технически вы можете вернуть другие комбинации монет (н-р 2 dimes, 1 nickel, 1 penny)

Запустите тесты в этом упражнении, чтобы увидеть ожидаемый результат. Затем напишите функцию convertToChange() в changeHandler.js чтобы проверить что тесты пройдены.