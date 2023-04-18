# chatgpt-automation2python
simple script to prompt chatgpt to write python scripts

## Prerequisite
ChatGPT API key

You can set your OpenAI API key as an environment variable in your operating system. Here are the steps for different operating systems:

For Windows:

Open a command prompt or PowerShell with administrative privileges. 
Set the environment variable using the following command:  
```setx OPEN_API_KEY "<YOUR_API_KEY>"```

For macOS and Linux:

Open a terminal window.  
Set the environment variable using the following command:  

```export OPEN_API_KEY="<YOUR_API_KEY>"``` 

Note: These commands will set the environment variable temporarily for the current session. If you want to set the environment variable permanently, you can add the setx or export command to your shell profile file (e.g., .bashrc or .bash_profile for Bash) so that it persists across terminal sessions.

## Usage  
```python3 python-chatgpt.py prompt filename```

## Example
```python3 python-chatgpt.py "write a python script that prints hello world" helloworld.py```
