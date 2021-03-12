OBJS:=cli
FLAGS:=main.o ./src/client.o
CFLAGS:=-I/home/wby/yuangongguanli/client/include

$(OBJS):$(FLAGS)
	$(CC) $^ -o $@ -lpthread -lsqlite3

.PHONY:clean

clean:
	rm $(OBJS) $(FLAGS)
