## Installation

Run the following from command to copy `hostfile.bat` to `C:\Users\%USERNAME%`.

Alternatively you can manually download hostfile.bat. **Note**: you'll have to make sure that the file is available via the [global PATH environment variable](https://superuser.com/a/143121/924637).

```
powershell -Command "(New-Object Net.WebClient).DownloadFile('https://raw.githubusercontent.com/Niellles/hostfile-command/main/hosts.bat', 'C:\Users\%USERNAME%\hosts.bat')"`
```
## Usage
After installation just run `hostfile` from the commandline to open your computers host file.

