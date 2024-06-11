# Generate SSL Certificate by Certbot and Letsencript

nGINX Server

1. Install wit apt
`sudo apt install nginx certbot python3-certbot-nginx`

or instal with snap

`sudo snap install core; sudo snap refresh core`
`sudo snap install --classic certbot`
`sudo ln -s /snap/bin/certbot /usr/bin/certbot`


2. Run:
`sudo certbot --nginx`
