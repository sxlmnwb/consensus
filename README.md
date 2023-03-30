# consensus
A brief info of the state of the consensus

<details>
  <summary>Requirements</summary>
  
  *  Ubuntu 20.04 
  *  Python3.8 
  *  Pip3

  For the correct work of the application you should configure RPC :26657 and REST :1317 endpoints.  
  For example :

  - ```API = "http://127.0.0.1:1317"```
  - ```RPC = "http://127.0.0.1:26657"```
  
</details>

<details>
  <summary>Installing</summary>
  
  Next open consensus.py in editor and replace REST/RPC variables with an appropriate values.  
  Example :
  
  ```REST = 'http://1.1.1.1:1317'```  
  ```RPC = "http://1.1.1.1:26657"```
  
  Once configured you can run the app by following:
  
  ```$ ./start ```
