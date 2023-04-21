# QwertyClient
This is a keylogger that can be run on any Windows device and send keystrokes to a netcat listener over a network

- You will be prompted with the following screen when you run the application:

![image](https://user-images.githubusercontent.com/101802030/233600641-7971e1ef-f42d-497c-849f-67d50147adbe.png)

- As you can see, the server ip address and port is required in order for keystrokes to sent across the network.

- A netcat listener can be started using the following command :
`nc -lvnp <port>`
