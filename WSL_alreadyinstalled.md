# If WSL is already installed

If after opening the Command Prompt or PowerShell as administrator, and then running `wsl --install`, a help text is shown, it means that you already have some version of WSL installed on your machine. 

<p style="text-align:left;">
<img src="images/wsl-already.png" alt="WSL is already installed on your machine" style="width:30%">
</p>

In that case, run the following command to get a list of available distributions (we want the **Ubuntu** one):

```
wsl -l -v
```

## If Ubuntu is already in the list of distributions

<p style="text-align:left;">
<img src="images/ubuntu-already.png" alt="Ubuntu is already in the list of distributions" style="width:30%">
</p>

Run 

```
wsl -s Ubuntu
```

to set the default distribution to Ubuntu. 


## If Ubuntu is not yet in the list of distributions

<p style="text-align:left;">
<img src="images/ubuntu-notyet.png" alt="Run wsl --install from CLI" style="width:30%">
</p>


Run 

```
wsl --install -d Ubuntu
```

to install the Ubuntu distribution, and then 

```
wsl -s Ubuntu
```

to set the default distribution to Ubuntu. 

## After Ubuntu distribution has been checked/installed

...you can now continue with [accessing the Unixshell](https://github.com/anastassiavybornova/pythoncrashcourse/blob/main/WSL_howto.md#accessing-the-unix-shell).