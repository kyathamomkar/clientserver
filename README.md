# clientserver
Implementation of the concepts of Distributed Systems by multi-client server program using java multithreading.

1. Multiple clients connecting to one server
2. Chat features between clients and server
3. Duplicate client username is ignored
4. Runtime directory creation for a new client connection and deletion upon disconnection
5. The files added to shared directory of a client are shared to other clients
6. If a shared file is updated, the same is updated across all clients
7. If a shared file is deleted at the owner client of that file, it takes votes to commit or ignore the deletion from other clients.
8. If all other clients agree to commit, the deleted file is removed from all the clients
9. Else, the deletion command is aborted, and the deleted file is recovered at the owner client.

For more detailed explanation, please watch the youtube video.
