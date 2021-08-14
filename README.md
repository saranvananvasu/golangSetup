# golangSetup
setup go debugger environment in macos

1) install Go SDK 

2) install Delve

3) install macos Developer tools in macos

4) install VS Code

4) install Go Developer tools and go langauge extension for VS Code

5) setup GOPATH environment var, ensure delve binary is added in the GOPATH

6) add the soruce code and under .vscode add launch.json and tasks.json

7) tasks.json is required for running delve as a seprate process which can be used to provde stdin inputs for the 
   program getting debugged

8) launch.json is required to invoke the go binary

