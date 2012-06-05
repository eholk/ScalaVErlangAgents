OBJS = client.beam plists.beam server.beam server2.beam

.PHONY: all
all : $(OBJS)

%.beam : %.erl
	erlc $<
