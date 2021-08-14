# golangSetup
setup go debugger environment in macos
---------------------------------------

1) install macos Developer tools in macos

2) install VS Code

3) install Go Developer tools and go langauge extension for VS Code

4) install Go SDK

5) install Delve

6) setup GOPATH environment var, ensure delve binary is added in the GOPATH

7) add the soruce code and under .vscode add launch.json and tasks.json

8) tasks.json is required for running delve as a seprate process which can be used to provde stdin inputs for the 
   program getting debugged

9) launch.json is required to invoke the go binary

10) run command+shift+B for running the task.json to run the dlv debugger. if this is not working for some reason, then 
copy the command and run it in the terminal manually. and then run the debugger using Run option -> Start Debuggings

11) when you hit the scanf in the source code, go to the delve debugger and give the input. To exit the code loop, run ctrl+D 
EOF which exits the scanf loop


# helpful links:

VS Code installation link:
https://code.visualstudio.com/docs/setup/mac

installing macos tools which is a prereq for installing gosdk and delve binaries:
https://apple.stackexchange.com/questions/254380/why-am-i-getting-an-invalid-active-developer-path-when-attempting-to-use-git-a - 

install delve binary for macos
https://github.com/go-delve/delve/blob/master/Documentation/installation/README.md

Go Download link
https://golang.org/dl/


setting up envs in macos
https://medium.com/@himanshuagarwal1395/setting-up-environment-variables-in-macos-sierra-f5978369b255

setting up envs for zsh in macos
https://apple.stackexchange.com/questions/356441/how-to-add-permanent-environment-variable-in-zsh

setting up delve debugger for getting stdin
https://stackoverflow.com/questions/50884981/how-to-read-input-when-debugging-go-in-visual-studio-code



