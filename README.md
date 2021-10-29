# ansible-workshop
## Notes
generate TLS certificate : `openssl req -x509 -nodes -days 30 -nwkey rsa:2048 -subj /CN=localhost -keyout files/nginx.key -out files/nginx.crt`
## References
Ansible Up and Running, 2nd Edition
by Lorin Hochstein, Rene Moser
