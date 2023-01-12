# Testing Github
The issue I had with connecting to my Github repo via SSH was because I hadn't added the private key to the SSH agent. Running this command in the .ssh folder solved the problem:

`ssh-add -K ~/.ssh/"add name of your public key here"`

# Testing Branching
Although I understand the theory of branching and it's utility, I haven't dealt with it in practice. Here we go!