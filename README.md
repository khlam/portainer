Example for locally running portainer and a docker registry.
Portainer login is 'admin' and '4444 4444 4444 4444'.

Hashed credentials were generated using:

src: https://gist.github.com/deviantony/62c009b41bde5e078b1a7de9f11f5e55

docker run --rm httpd:2.4-alpine htpasswd -nbB admin '4444 4444 4444 4444' | cut -d ":" -f 2
