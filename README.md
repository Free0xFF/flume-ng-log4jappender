# flume-ng-log4jappender

When I use LoadBalancingLog4jAppender to send data to flume, it throws StackOverFlow Exception because of not initiating parameter maxIoWorkers, so I fix the bug and it works.

