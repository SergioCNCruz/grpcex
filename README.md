# grpcex
Exemplo muito básico do uso de grpc com python 

-----------------------------------
$ pip install grpcio
$ pip install grpcio-tools

$ python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. calculator.proto


-----------------------------------
$ python server.py
Starting server. Listening on port 50051.


-----------------------------------
$ python client.py
