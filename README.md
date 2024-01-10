# my-wordpress-server

I wanted to create a simple minimalist website to showcase my resume/cover letter and blogs about my personal projects hosted on GitHub.

This was done via deploying a Nginx server connected to Wordpress server. In order to accomplish that I spun up a simple VM on Hetzner and configured a firewall there, I have also bought a domain ptisma.xyz using Namecheap.

For SSL/TLS certificates, Certbot was used.

I wanted to be as DevOps-y as possible, minimal development, so all the instances are dockerized and deployed on VM via docker-compose. Once everything was up, Wordpress was further configured using GUI.