Практическое задание №4 по курсу Java для тестировщиков:

 - Реализовать (на Spring) приложение, которое умеет считать слова:
   на вход в @RestController post-запросом отправляете WordCountRequest в котором лежит String.
   Нужно вернуть количество вхождения слов, по популярности:
   для строки «Grut! I am grut!’
 - Ответ будет:
   {words: [{“grut”: 2}, {“i”: 1}, {“am”: 1}]}
 - Корректность работы со строкой протестировать следующим образом:
   - На простой строке
   - Положить в папку test/resources
   Книгу (Lord of the rings или Dune) и посчитать в ней слова