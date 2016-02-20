#Update Certificates for Ubuntu
1.	Download certificates (.crt file) 
\\107.113.53.70\Public\SVMC_IS\01. IS Setup\Setup\Fix certificate errors
2.	Copy certificates files to /usr/share/ca-certificates 
3.	Let Ubuntu add the '.crt' file's path relative to /usr/share/ca-certificates to /etc/ca-certificates.conf
4.	Update certificate with following command
sudo update-ca-certificates -f
