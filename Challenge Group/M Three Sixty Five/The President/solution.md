# Solution
- Check AADInternals documentation https://aadinternals.com/aadinternals/ to find the right command to display the flag.
```bash
Get-AADIntUsers | Select UserPrincipalName,PhoneNumber
```

![Alt text](image.png)
