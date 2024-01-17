## Вариант 11. Решение дифференциального уравнения y' + y = f(x) (fx) явным методом Эйлера на отрезке от 0 до [limit]. Беляков Данила, ИУ6-14М

### Build
- server: gcc server.c - o server -lm -lpthread
- client: gcc client.c - o client -lm -lpthread
### Run
- server: ./server [numofcpus]
- client: ./client [limit] [y0]

### Комментарии:
- В файле output.txt результат генерации решения дифф. уравнения y'+y=x^2, y(0)=2 на отрезке [0, 10]
- В файле graph.ipynb графики с численного решения и аналитического решения уравнения по формуле.
