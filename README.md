# worxpace

**worxpace** is a simple bash script that helps to group your favorite **apps**, **websites**, and **files** so that you can open them easily at once!

### What are **"worxpaces"**?

worxpace creates groups called **"worxpaces"**, these groups have all your grouped apps, websites, and files.

## Let's set things up! 🛠

Add it to path and run it from everywhere. You can easily do it in 2 ways:

**1**. Create a symlink to the worxpace file **(recommended)**.
```bash
sudo ln -s <Absolute path to the worxpace file> /usr/local/bin/worxpace
```
**OR**

**2**. Add worxpace file to /usr/local/bin.

## How to use? 🤔

worxpace is super easy to use!

It has 7 easy to remember options:

- **Create a new worxpace:**
   ```bash
   worxpace -n|--new
   ```

- **Add apps/websites/files to an existing worxpace:**
   ```bash
   worxpace -a|--add <Worxpace_Name>
   ```

- **Open the things in a worxpace(s):**
   ```bash
   worxpace -o|--open <Worxpace_Name...>
   ```

- **List the things in a worxpace(s):**
   ```bash
   worxpace -l|--list <Worxpace_Name...>
   ```

- **List all worxpaces:**
   ```bash
   worxpace -lw|--listworxpaces
   ```

-  **Remove an app/website/file from a worxpace:**
   ```bash
   worxpace -r|--remove <Worxpace_Name> <App/website/file_name>
   ```

- **Remove a worxpace(s):**
   ```bash
   worxpace -rw|--removeworxpaces <Worxpace_Name...> 
   ```

## Contributors 👨‍💻:

- [Mohammed Gaiban Khan](https://github.com/Gaiban-Khan)
