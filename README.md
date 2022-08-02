
# FIGRIT: A File Integrity Monitor

FIGRIT is a standard FIM built into Powershell using the SHA512 algorithm. It creates a baseline for all files to be monitored at a given point in time. And till the app is running in the powershell, it alerts the user of any *changes* or *deletions* in the file.

## Run Locally

1. Clone the project

```bash
  git clone https://github.com/nixxby/FIGRIT
```
2. Open Powershell/cmd 
3. Go to the project directory
4. Run the /main.ps1 file by giving it's full address
5. Choose option A at the first time to create a baseline
6. Now that the baseline is created, any changes/deletions will be monitored in realtime.


## Screenshots

![FIGRIT Screenshot1](https://github.com/nixxby/FIGRIT/blob/main/screenshot1.png?raw=true)
