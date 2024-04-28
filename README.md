<div id="SealedSaucer" align="center">
    <h1>Online Self</h1>
    <p>Make Your Discord Account 24/7 Online!</p>
    <br>
    <img src="https://i.imgur.com/N61T21L.png" height="210">
</div>

---

<p align="center">
<br>

## Warning
**DO <ins>NOT</ins> GIVE YOUR DISCORD TOKENS TO ANYONE.**
#### Giving your token to someone else will give them the ability to log into your account without the password or 2FA.

## Features
- 🔒 Secure
- Supports Custom Status
- Account will stay 24/7 online (if you set it up correctly)
- Supports all three status modes (Online, Idle, Do Not Disturb)
- Can be used almost on any platform that supports [Python](https://python.org)

## Obtaining Your Token 
You will need an user token inorder to use this code. You can obtain it by doing the following:
1. Logging in to your discord account
2. Pressing `Ctrl+Shift+I` to open Chrome Developer Tools
3. Go to the `Network` Tab
4. Keep it open and refresh the page
5. Type `/api` in the filter search box
6. Click the entry that has `science` as the `Name`
7. On the sub-menu, go to `Headers`
8. Scroll down till you see an entry named `Authorization`. Copy the line next to it.
9. This is your token, <ins>**DO NOT GIVE IT TO ANYONE**</ins>.

## Installation
### · Replit
#### The code inside the repository was originally made to be hostable on [Replit](https://replit.com), but due to a recent ban on all repositories that are against Discord's ToS, you won't be able to import this repository directly to Replit anymore.
#### Here's a workaround to solve that issue:
1. download the latest version of this code.
2. Unzip the file
3. Create a new Python repl on [Replit](https://replit.com)
4. Upload the files into the repl (Just drag and drop it into the files sidebar)
5. Overwrite the files if a prompt pops-up
6. Add your token inside Secrets with `TOKEN` as the key and your token as the value
7. Modify both the status mode and custom status, if you want to make any adjustments
8. Run the repl

### · Local Installation
1. Install [Python](https://python.org/downloads) on your machine 
2. Copy the code below
<details>
<summary> Click here to view the code, and click again to close it</summary>
<br>

</details>

3. Create a new Python file and paste the code into it
4. Modify both the status mode and custom status, if you want to make any adjustments
5. Save the file
6. Create a `requirements.txt` file and copy and paste the file contents inside [requirements.txt](https://github.com/SealedSaucer/Online-Forever/blob/main/requirements.txt) without the `Flask` module
7. Save the file
8. Open command prompt where both the files are present and run `pip install -r requirements.txt`
9. Once the packages are downloaded, either double-click the python file in order to run it or open command prompt where the python file is present and run `python filename.py`

## Known Errors And How To Fix Them
### [Discord] Status mode not changing
<details>
<summary>Click here to view the explanation and fix</summary>
<br>
Just wait for a few minutes. It takes some time for Discord to refresh your status.
</details>

### [Replit] This repository could not be accessed, try again later/This repository possibly violates our Terms of Service. Contact support if you believe this is a mistake.
<details>
<summary>Click here to view the explanation and fix</summary>
<br>
As I mentioned before, due to a recent ban on all repositories that are against Discord's ToS, you won't be able to import this repository directly to Replit anymore. 
</details>

### [Replit] sh: line 1: python3: command not found
<details>
<summary>Click here to view the explanation and fix</summary>
<br>
You cloned it into a bash repl. Make sure you select "Python" from the languages list when you create the repl.
</details>

### [Replit] Cloudflare Error/Temporarily banned from accessing Discord's API
<details>
<summary>Click here to view the explanation and fix</summary>
<br>
This happens because repls have Shared Public IP Addresses, and some Replit Users abuse the platform to spam (through self bots or nukers). Whenever Discord sees lots of invalid requests coming from a single IP address, it will use Cloudflare to temporarily block any incoming requests.

#### Fix:
- Go to shell
- Enter <code>kill 1</code>
- Wait for the repl to reload
- Run the repl again
</details>

### [Replit] ModuleNotFoundError: No module named 'websocket'
<details>
<summary>Click here to view the explanation and fix</summary>
<br>
Run <code>pip install websocket</code> in the shell
</details>

### [Replit] TypeError: WebSocket.__init() missing 3 required positional arguments: 'environ', 'socket', and 'rfile'
<details>
<summary>Click here to view the explanation and fix</summary>
<br>
Run <code>pip install websocket-client</code> in the shell
</details>

---

<p align="center">❤️ Online Forever is licensed under GNU General Public License.</p>
