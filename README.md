<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="MAS Logo"></p>

<h1 align="center">Microsoft  Activation  Scripts (MAS)</h1>

<p align="center">Open-source Windows and Office activator featuring HWID, Ohook, TSforge, and Online KMS activation methods, along with advanced troubleshooting.</p>

<hr>
  
## How to Activate Windows / Office / Extended Updates (ESU)?

### Method 1 - PowerShell ❤️

1. **Open PowerShell**  
   Click the **Start Menu**, type `PowerShell`, then open it.

2. **Copy and paste the code below, then press enter.**  
   - For **Windows 8, 10, 11**: 📌
     ```
     irm https://get.activated.win | iex
     ```
	 If the above is blocked (by ISP/DNS), try this (needs updated Windows 10 or 11):  
	 ```
	 iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
	 ```
   - For **Windows 7** and later:
     ```
     iex ((New-Object Net.WebClient).DownloadString('https://get.activated.win'))
     ```
	- **Script not launching❓Use the below-listed Method 2.**

3. The activation menu will appear. **Choose the green-highlighted options** to activate Windows or Office.

4. **Done!**

---

### Method 2 - Traditional (Windows Vista and later)

1.   Download the script: [**MAS_AIO.cmd**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true) or the [full ZIP](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?$format=zip).
2.   Run the file named `MAS_AIO.cmd`.
3.   You will see the activation options. Follow the on-screen instructions.
4.   That's all.

---

> [!TIP]
> - Some ISPs/DNS block access to our domains. You can bypass this by enabling [DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) in your browser.  
> - **Having trouble**❓Visit our [troubleshooting page](https://massgrave.dev/troubleshoot) or raise an issue on [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts/issues).

---

- To activate additional products such as **Office for macOS, Visual Studio, RDS CALs, and Windows XP**, check [here](https://massgrave.dev/unsupported_products_activation).
- To run the scripts in unattended mode, check [here](https://massgrave.dev/command_line_switches).

---

> [!NOTE]
>
> - The IRM command in PowerShell downloads a script from a specified URL, and the IEX command executes it.
> - Always double-check the URL before executing the command and verify the source if manually downloading files.
> - Be cautious, as some spread malware disguised as MAS by using different URLs in the IRM command.

---

```
Latest Version: 3.9
Release date: 19-Nov-2025
```

### [Troubleshooting / Help](https://massgrave.dev/troubleshoot)
### [Download Original Windows & Office](https://massgrave.dev/genuine-installation-media)
### Homepage - [https://abhynex.github.io/](https://abhynex.github.io)

<div align="center">
  
[![1.1]][1]
[![1.2]][2]
[![1.3]][3]

</div>

<div align="center">
  
[![1.4]][4]
[![1.5]][5]
[![1.6]][6]
[![1.7]][7]

</div>
<p align="center">by Abhishek</p>



