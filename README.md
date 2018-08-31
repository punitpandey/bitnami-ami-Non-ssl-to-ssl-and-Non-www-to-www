# bitnami-ami-Non-ssl-to-ssl-and-Non-www-to-www
This repository is to redirect non-www to www and non ssl to ssl website
Update mysite with your site name.
Put CSR file and private key file to '/opt/bitnami/apps/wordpress/conf/certs/' directory, if 'certs' directory doesn't exist create one and put both files there.
Update crt_file_name with your CRT file name.
Update private_key_name with the private key name that was created at the time of CSR file generation.
