An image processing server is being designed that interacts with the client and server which includes a main thread and a pool of worker threads.
Producer-consumer model is used to interact with client and server.
Higher priority is assigned to main thread which accepts client requests and places data in a bounded buffer which will be serviced by    worker threads and utilized synchronization services.
OpenCV platform is used for image processing operations on input image of the client.
