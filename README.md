# asd124
The application to be able to run needs the following steps:

1) Import the eclipse project from the archive import 
2) Set up java compiler with jdk version 1.8
3) Before running the application you need to run rmirepository:
creating in eclipse a run configuration having as location:
C: \ Program Files \ Java \ jdk1.8.0_201 \ bin \ rmiregistry.exe
and as working directory: the bin folder of the project:
$ {workspace_loc: / GenesysGame / bin}
4) The Server run configuration must be set with the following VM arguments:
-Djava.security.policy = file: $ {workspace_loc} /GenesysGame/security.policy -Djava.rmi.server.codebase = file: $ {workspace_loc} / GenesysGame / bin /

the images of the various steps are attached
