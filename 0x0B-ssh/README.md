- Run the ssh-keygen command.

- You can use the -t option to specify the type of key to create.

- For example, to create an RSA key, run:

- ssh-keygen -t rsa

- You can use the -b option to specify the length (bit size) of the key, as shown in the following example:

- ssh-keygen -b 2048 -t rs

- to loge in your server you should write this commands 

- eval $("ssh-agent")

- ssh-add ~/.ssh/school

- ssh ubuntu@"your ip addres"
