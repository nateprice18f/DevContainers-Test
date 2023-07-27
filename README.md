# Dev Container setup and use cases

## Dev Container Setup
1. Install Visual Studio Code. download here.
2. Install Docker Desktop, download here.
3. Install the Dev Container extension, found here.

## Using Dev Container from Git repo
1. Clone repo to local system  
2. Open repo folder in VSCode
3. Hit F1 to open "Command Palette"
4. Type "Dev Containers: Open Folder in Container" and select 
5. Select the container folder to be used. 
6. The VSCode will reload
7. Once reloaded, the tab to the bottom left will show which container is being used.
Note: 
- This will start a contianer in Docker Desktop. You can check which container you are using by checking the container ID in VSCode terminal with the container ID in Docker Desktop.
- You can have more than one Dev Container running. The option at this time; open another VSCode window and follow the steps above.
- You can detach from a running container without stopping it:
    - File > Close Remote Connection 
    - Hitting F1 to open "Command Palette". Then type "Remote - Close Remote Connection"
    - Clicking on the remote tab(Tab bottom left)  > Close Remote Connection
- To stop the running container and return to the local directory. 
    - File > <To be Updated> 
    - Clicking on the remote tab(Tab bottom left)  > Repoen locally
    - docker stop container ID or container name
 
## Creating our own Dev Container
  


 