# EZ CONNECT
Manage your ssh keys and connections easily with ez-conenct.

# Supported shells

```
0. Mac default Terminal 
1. iTerm
2. Tmux
```

# Check if your terminal shell is supported
Run the following command to see if your shell is supported. If you can see your ssh Agent pid, if you don't see your ssh Agent pid, I suggest you use a shell that is listed on the Supported shells section above. 
```
eval $(ssh-agent -s)
```

# Install Dependencies

```
Ez-connect has 0 dependencies. Ez-connect will work with any unix type terminals that has a running ssh-agent. Just simply follow the installation guide below and let the magic happen.
```


# Install Ez-connect

```
$ git clone https://github.com/maclaine-san/ez-connect.git
$ sudo cp ez-connect/ez-connect /usr/local/bin/
```

# Usage

```bash
$ ez-connect
**********************************************************
*                                                  __    *
*      ___  ___   ____ ___   ___   ___  ___  ____ / /_   *
*     / -_)/_ /  / __// _ \ / _ \ / _ \/ -_)/ __// __/   *
*     \__/ /__/  \__/ \___//_//_//_//_/\__/ \__/ \__/    *
*                                                        *
*                   version 0.1.0                        *
*        https://github.com/maclaine-san/ez-connect      *
*                                                        *
**********************************************************

Manage all your ssh connections easily with ez-connect.

Your available ssh keys in ~/.ssh directory.
-----------------------------------------------
id |    ssh key file
-----------------------------------------------
0. /Users/maclaine-san/.ssh/id_rsa
1. /Users/maclaine-san/.ssh/id_rsa_singapore
2. /Users/maclaine-san/.ssh/id_rsa_australia
3. /Users/maclaine-san/.ssh/id_rsa_philippines
-----------------------------------------------
Enter ssh key id.
```

