As a workaround for disabled script execution, run this command in an elevated PowerShell windows first and choose "all" if you're asked where to apply this:

```Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass```

Or:

```Set-ExecutionPolicy RemoteSigned```

and Answer: A
