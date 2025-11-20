# DOWNLOADING FILES AND SERVICE CONTROL

## DOWNLOAD FILES FROM INTERNET
- `wget <URL_of_file>` OR `wget -O <CustomName>.txt <URL> ` - download file from internet
- `curl <URL>` - call API
- `apt` OR `yum/dnf install <AppName>` - install application (apt = Ubuntu) (yum / dnf = RedHat / CentOS / Fedora family)
- `rpm -qa | grep <App_Name>` OR `dnf list installed` - check if application is installed OR not , gives the list of all installed applications
- `yum/dnf list` OR `apt search <PackageName>` - list available packages to install

## SERVICE CONTROL
- `systemctl start/stop/status <ServiceName>` - start OR stop OR status of a service
- `systemctl list-units --type=service --all` - list all services
