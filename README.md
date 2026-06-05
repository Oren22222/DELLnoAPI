1.) Dell Warranty checker tool, this does not require an API like the previous tool.

2.) It will check for warranty expire dates and warranty start/ship date.

3.) The use case for this was for me to bulk processing of service tags so i did not have to check this one by one on the dell service tag checker in the support section of their website.

4.) You can upload txt or csv of service tags and begin processing, NOTE: it is quite slow as it scarpes the web and checks 1 by 1 but much quciker than a human. 150 tags will take around 5 minutes.

5.) Once you have started processing it will open a powershell window each time it processes as it uses PowerShell with .NET HttpClient to call Dell's API. .NET handles cookies and TLS properly, bypassing WAF issues.

<img width="1168" height="768" alt="image" src="https://github.com/user-attachments/assets/eca7b624-58d6-454d-8c7f-fde33af9fb53" />
