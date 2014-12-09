#airtime for CentOS
==============

This script will install all the necessary libraries and applications to compile, setup and run Airtime on CentOS 6.  This should work on all RedHat based systems (fedora, rhel, etc).
  
  
###Required Items
*  **_Install_:** EPEL Repo via YUM repos
  *  ``` sudo yum -y install epel-release ```
*  **_Install_:** RepoForge Repo via YUM repos 
  *  ``` sudo yum -y install rpmforge-release ```

###Installed Items
* tarballs setup / used by the installer
  * ```<hold>```
*  EPEL packages setup / used by installer
  * ``` <hold> ```
*  RepoForge packages setup / used by installer
  * ``` <hold> ```
*  base packages setup / used by installer
  * ``` <hold> ```







#####TODO
- [ ] refactor:  break installer into seperate tasks
- [ ] refactor:  if it lives in CentOS Base, leave it (unless we know we put it down on the system)
- [ ] uninstaller:  we should be able to remove everything we installed technically
