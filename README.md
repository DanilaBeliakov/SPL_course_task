## Вариант 11. Решение дифференциального уравнения y' + y = f(x) (f(x)=x^2) явным методом Эйлера на отрезке от 0 до [limit]. Беляков Данила, ИУ6-14М

### Build
- server: gcc server.c - o server -lm -lpthread
- client: gcc client.c - o client -lm -lpthread
### Run
- server: ./server [numofcpus]
- client: ./client [limit] [y0]

### Комментарии:
- В файле output.txt результат генерации решения дифф. уравнения y'+y=x^2, y(0)=2 на отрезке [0, 10]. Аналитическое решение y(x)=c1*e^(-x)+x^2-2x+2.
- В файле graph.ipynb графики численного решения и аналитического решения уравнения по формуле. Графики численного и аналитического решений совпадают.
- Сделать makefile для сборки проекта не получилось(
