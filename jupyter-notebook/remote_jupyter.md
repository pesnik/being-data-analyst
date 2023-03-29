```sh
# on remote pc
jupyter notebook --no-browser --port=8081

# ssh tunneling on local pc
ssh -L 8080:localhost:8081 meatbas3@ip -p port
```
