# Nginx-proxy

### To Install

1. Create a new folder and enter it
`mkdir nginx-proxy`
`cd nginx-proxy`
2. Clone this repository
`git clone git@github.com:2srqc/nginx-proxy.git .`
4. Make a copy of .env.example as .env
`cp .env.example .env`
6. Edit .env and fill in the default email for LetsEncrypt certs.
`nano .env`
8. When done editing, Press Ctrl-X, then Y, then Enter to save and quit nano.
9. Start the docker compose project
`docker compose up -d`
