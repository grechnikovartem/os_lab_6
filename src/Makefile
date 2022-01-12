all_done: worker client

worker: worker.c
	gcc worker.c -lzmq -o worker
	
client: client.c ball_tree.h
	gcc client.c ball_tree.h -lzmq -o client
