# analytics_AB_testing_dataapp
Analysis of a new algorithm for selecting partners in a dating app (A/B test)
Анализ нового алгоритма подбора партнеров в приложении для знакомств(А/Б тест)

Проиложение для онлайн знакомств.
Механика приложения следующая: пользователи видят в приложении анкеты друг друга и могут ставить друг другу лайки или дизлайки. Если пользователи поставили друг другу лайк – это называется мэтч, и у пользователей появляется возможность познакомиться.

Команда приложения разработала новый алгоритм для поиска наиболее подходящих анкет. Для проверки работы алгоритма был проведен АБ-тест. Все пользователи были разделены на две группы. Пользователи в группе с номером 0 пользовались приложением со старым алгоритмом. Все пользователи в группе 1 пользовались приложением с новым алгоритмом для поиска анкет.

В данных находится выгрузка логов взаимодействия пользователей друг с другом. Для каждой пары пользователей указано, из какой они группы АБ-теста и случился ли у них мэтч.

Необходимо оценить, правда ли, что новый алгоритм улучшил качество сервиса.

Анализ и аналитическое заключение с ответом на вопрос внутри statistic_ab_test_datingapp.ipynb.
Данные внутри dating_data.csv.
