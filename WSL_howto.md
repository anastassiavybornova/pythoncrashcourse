# WSL: Windows Subsystem for Linux. Motivation & installation

## Intro: WSL, why?

If you have a Windows machine and you have installed the Anaconda Distribution, then you already have several command line interfaces (CLIs) on your machine:
1. Windows PowerShell (comes with Windows)
2. Command Prompt (comes with Windows)
3. Anaconda Prompt (came with the Anaconda distribution)

Until now, Windows users in this class have been directed to use the **Anaconda Prompt**. However, later during class, you will also learn how to use the **Unix shell** - another very commonly used CLI (and the one installed on macOS by default, called "Terminal"). 

Therefore, as Windows user, you need to install WSL - Windows Subsystem for Linux (read more about WSL [here](https://learn.microsoft.com/en-us/windows/wsl/about)). In short, installing WSL on your Windows machine will add a 4th CLI, the Unix shell, to your machine; this will allow you to **use a Unix shell** on your Windows machine. 

## Instructions: WSL, how?

Find the detailed official instructions [here](https://learn.microsoft.com/en-us/windows/wsl/install). TLDR: If all goes well, all you need to do is: 
1. Open a CLI - either **Windows PowerShell** or **Command Prompt** (NOT Anaconda Prompt) - as **administrator** (search doe "Command" or "PowerShell" in Applications, then "open as administrator")
2. Run from the CLI: `wsl --install` - this will **by default** install the Ubuntu distribution of Linux (which is the one we want)
3. Restart your computer; at restart, the Ubuntu application will open automatically
4. Set your username and password

**Step 1: Open CLI as Administrator**

<figure>
  <img src="images/cmd.png" alt="Open Command Prompt as Administrator" style="width:50%">
  <figcaption>Step 1: Open CLI (shown here: Command Prompt) as administrator</figcaption>
</figure>

**Step 2: `wsl --install`**

** Step 3 & 4: After restart, set username & password

> **Note** If running `wsl --install` doesn't look like in the screenshot above, but instead shows you a help text (as in the screenshot below), it means that you already have some distribution of WSL installed. Click here for instructions what to do next [INSERT LINK TO MD 2].

### Accessing the Unix shell

Now, you should be able to open the application `Ubuntu` from your Windows machine. Click on the Windows symbol and type "Ubuntu" to search for the application, then open it.

[INSERT UBUNTU]

## Outro: WSL, what's next?

After successfully installing WSL, you will have four shells on your machine:
1. Windows PowerShell (came with Windows)
2. Command Prompt (came with Windows)
3. Anaconda Prompt (came with the Anaconda distribution)
4. Unix shell (came with WSL)

You are welcome to continue using the Anaconda Prompt for all things python and conda. For the lecture & exercise on shell scripting, you will need to use the Unix shell.