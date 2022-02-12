#Target_name : Dependecnies
#<Tab>Command
SRC = src/main.c\
src/module.c 
INC = inc 

all.out : $(SRC) 
	 gcc $^ -I$(INC) -o $@

	
run: target
	./all.out

clean:
	rm all.out