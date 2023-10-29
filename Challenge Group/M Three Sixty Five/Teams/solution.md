# Solution
- Check AADInternals documentation https://aadinternals.com/aadinternals/ to find the right command to display the flag.
```bash
Get-AADIntTeamsMessages | Format-Table id,content,deletiontime,*type*,DisplayName
```

![Alt text](image.png)
