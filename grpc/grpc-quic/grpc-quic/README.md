draft: GRPC over UDP (powered by QUIC)
Changes made to GRPC: <br />
The test files server.go and client.go are used to test RPC operations over QUIC. It uses the same ceritficate in each new connection, thus ensuring 0-rtt handshakes <br />
.proto file specifies the rpc functions and objects, with the repeated syntax for big object size <br />
