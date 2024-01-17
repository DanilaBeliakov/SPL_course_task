## Вариант 11. Решение дифференциального уравнения y' + y = f(x) явным методом Эйлера на отрезке от 0 до [limit]. Беляков Данила, ИУ6-14М

### Build
- server: gcc server.c - o server.o -lm -lpthread
- client: gcc client.c - o client.o -lm -lpthread
### Run
- server: ./server.o [numofcpus]
- client: ./client.o [limit] [y0]
