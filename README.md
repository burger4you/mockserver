# mockserver
Mock Server for Health Gorilla API testing

To run MockServer asynchronously as a forked JVM:

mvn mockserver:runForked

To stop a forked instance of MockServer running on the same machine:

mvn mockserver:stopForked

The stopForked goal does assumes that MockServer is running on the same physical machine as it uses 127.0.0.1 to communicate with MockServer stop socket.
