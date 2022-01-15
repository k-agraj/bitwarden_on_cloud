# ReadMe - bitwarden_on_cloud
This describes steps for setting up Bitwarden: In-Premise personal password vault on cloud.
Steps to follow: -
- Create No-Ip Account (https://www.noip.com/sign-up). Help to setting up a No-Ip account can be found at support page (https://www.noip.com/support/knowledgebase/create-free-dynamic-dns-account-ip-noip-com/).
- Preserve the credentials to be used later.
- Add hostname - search desired free domain (with free No-Ip account you need to refresh every 30 days)
- Create Ubuntu EC2 instance on preferred cloud service (AWS, Google Cloud, Azure).
- Install Make
- Install GCC
- Setup No-Ip DDNS Service
-	Setup Docker Community Edition
-	Install Bitwarden on Docker
-	Disable Self Registration
