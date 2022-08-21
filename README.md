# GIT-SSH-SCP-MANAGER (gssm)
Manage your ssh keys and connections easily with GSSM.

# Supported shells

```
1. Mac default terminal 
2. iTerm
3. Tmux
```

# Check if your terminal shell is supported
Run the following command to see if your shell is supported. If you can see your ssh Agent pid, if you don't see your ssh Agent pid, I suggest you use a shell that is listed on the Supported shells section above. 
```
eval $(ssh-agent -s)
```

# Install Dependencies

This package requires 0 dependencies.
This will work with any unix type terminals that has a running ssh-agent. Just simply follow the installation guide below and let the magic happen.


# Installation

```
$ git clone https://github.com/maclaine-san/ez-connect.git
$ sudo cp git-ssh-scp-manager/gssm /usr/local/bin/
```

# Usage
Note: If you want to use git command option, you should be in the directory of the project that you want to manage.
```bash
$ gssm

**********************************************************
*                                                        *
*                                                        *
*    ********     ********    ********   ****     ****   *
*   **//////**   **//////    **//////   /**/**   **/**   *
*  **      //   /**         /**         /**//** ** /**   *
*  /**           /*********  /*********  /** //***  /**  *
*  /**    *****  ////////**  ////////**  /**  //*   /**  *
*  //**  ////**         /**         /**  /**   /    /**  *
*   //********    ********    ********   /**        /**  *
*   ////////    ////////    ////////    //         //    *
*                                                        *
*                   version 0.1.0                        *
*   https://github.com/maclaine-san/git-ssh-scp-manager  *
*                                                        *
**********************************************************

Manage all your ssh connections easily with ez-connect.

What do you want to do next?
-----------------------------------------------
1. git command
2. ssh to server
3. scp files
4. exit
-----------------------------------------------
Enter choice: 1

Your available ssh keys in ~/.ssh directory.

-----------------------------------------------
id |    ssh key file
-----------------------------------------------
0. /Users/mac/.ssh/id_rsa
1. /Users/mac/.ssh/id_rsa_gitlab
2. /Users/mac/.ssh/id_rsa_github
3. /Users/mac/.ssh/id_rsa_bitbucket
-----------------------------------------------
Enter ssh key id: 1
Identity added: /Users/mac/.ssh/id_rsa (mac@macbook.lan)
Enter git username: maclaine-san

Getting current branch info:
* main

Available Git commands.
-----------------------------------------------
1. git pull <branch> only
2. git push <branch> only
3. super push = git add <files> -> git commit <message> -> git push <branch>
4. exit
-----------------------------------------------
Enter git command choice: 1
```

