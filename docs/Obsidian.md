This entire repo can be opened, navigated, and managed using Obsidian.
# Download
Visit: https://obsidian.md/download

Install Obsidian.
# Setup `git` to sync changes
Install git: https://git-scm.com/install/

You should clone the repo using `git`.

# Open this Repo
Open this repo by clicking on `Open Vault` and select the directory: `rc-designs`

# Add the `git` Obsidian Plugin
Press `CTRL+,` / `CMD+,`and under *Community Plugin* -> (understand the risk here) *Turn on Community Plugins* -> *Browse* -> Install `Git` By *Vinzent*:
- [Obsidian Git Plugin](obsidian://show-plugin?id=obsidian-git)
Then click on: *Enable*

In *Options* for the *Obsidian Git* plugin you need to set automatic push and pull:
![Options for the Obsidian Git plugin](attachments/Pasted%20image%2020260104134245.png)

From this point on all of your changes will automatically push to the server that you make on that machine (as long as Obsidian is open) and if new designs are pushed it will automatically pull them.

To verify it is working use`CTRL+P` or `CMD+P` and run:
- `Git: Commit` to commit your local changes
- `Git: Push` to push your local changes to GitHub 
- `Git: Pull` to pull others changes
- If you wait for 10 minutes from last edit it will auto-commit and push your changes, and every 30 minutes it will pull down the latest changes from others