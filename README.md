## Description

 <pre>  
       WINspect is part of a larger project for auditing different areas of Windows environments.         
    It focuses on enumerating different parts of a Windows machine aiming to identify security weaknesses       
    and point to components that need further hardening. The main targets for the current version are 
    domain-joined windows machines. Howerver, some of the functions still apply for standalone workstations.

 </pre>

## Features

This current version of the script supports the following features :

- Checking for installed security products.
- Enumerating world-exposed local filesystem shares.
- Enumerating domain users and groups with local group membership.
- Enumerating registry autoruns.
- Enumerating local services that are configurable by Authenticated Users group members.
- Enumerating local services for which corresponding binary is writable by Authenticated Users group members.
- Enumerating non-system32 Windows Hosted Services and their associated DLLs.
- Enumerating local services with unquoted path vulnerability.
- Enumerating non-system scheduled tasks.
- Checking for DLL hijackability.
- Checking for User Account Control settings.
- Checking for unattended installs leftovers.

## Supported Powershell Version

   This version was tested in a powershell v2.0 environment.
   

## Contributions

You are welcome to contribute and suggeste any improvements.
If you want to point to an issue, Please [file an issue](https://github.com/A-mIn3/WINspect/issues).

## Direct contributions

Fork the repository && File a pull request && You are good to go ;)
 
## Need Help

If you have questions or need further guidance on using the tool , please [file an issue](https://github.com/A-mIn3/WINspect/issues). 

## License
This project is licensed under The GPL terms.
