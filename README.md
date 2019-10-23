# ECE-365-P2

This program provides a user with the functionality of a priority queue of nodes using a binary heap implementation, provided a given capacity. It provides the functions:


-insert: inserts a node with specified id string, key, and optionally a pointer.
	  returns 0 on sucess, 1 if heap is filled to capacity, and 2 if the node with given id already exists.


-setKey: sets the key value of the node with the specified id to the specified key vales.
	  returns 0 on success, and 1 if the given id does not exist.


-deleteMin: deletes node with smallest key, and returns its data (id, key, and pointer) if provided.
	  returns 0 on success, and 1 if the heap is empty.


-remove: deletes a node with specified id, and returns its data (key and pointer) if provided.
	  returns 0 on success, and 1 if the given id doesn't exist.
