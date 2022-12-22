# VSCodeLinuxStable
This repository contains a Github action that downloads [WSL server update](https://update.code.visualstudio.com/latest/server-linux-x64/stable), for those machines that behind a certain proxy that cannot download the file as vscode upgrades.

## Step
1. Go to https://github.com/okatsn/VSCodeLinuxStable/actions and manually run the action
2. Download [files/stable](https://github.com/okatsn/VSCodeLinuxStable/blob/master/files/stable)
3. Place the downloaded file to the corresponding folder named by commit hash under the following (exemplary) directory:
   - ["C:\Users\<user_name>\AppData\Local\Temp\vsch\serverCache\<commit_hash>\"](../AppData/Local/Temp/vsch/serverCache) with the file renamed as **vscode-server-linux-x64.tar.gz**
   - ["C:\Users\<user_name>\AppData\Local\Temp\vscode-remote-wsl\<commit_hash>\"](../AppData/Local/Temp/vscode-remote-wsl) with the file renamed as **vscode-server-stable-linux-x64.tar.gz** 
