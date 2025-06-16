# SSH-hardening-windows
 SSH Hardening on Windows using OpenSSH

This project demonstrates secure SSH configuration on a Windows machine by disabling password-based authentication and enabling only key-based access.
 Features

- Configured OpenSSH server to use only public key authentication
- Disabled insecure password login and challenge-response prompts
- Secured `.ssh` directory permissions using PowerShell
- Verified setup using verbose `ssh -v` logs
- Supports access via non-default port `2222`
Technologies Used

- Windows 10 / 11
- OpenSSH for Windows
- PowerShell
- SSH (client + server)
How to Test

```bash ```
ssh yourusername@localhost -p 2222 

-FOR REMOTE USE 

ssh yourusername@<Your-PC-IP> -p 2222

![Administrator_ Windows PowerShell 16-06-2025 09_42_58](https://github.com/user-attachments/assets/2594adbe-5e92-4869-98be-9cb13faea6c0)

