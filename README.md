# Simple Pi-hole + Unbound docker configuration

Setup [Pi-hole](https://pi-hole.net/) as dhcp server and [as all-around DNS solution](https://docs.pi-hole.net/guides/dns/unbound/) in raspberry pi using [docker](https://www.docker.com/) container!

## Steps

- Install docker
- Clone this repo
- Edit TZ & WEBPASSWORD variable in docker-compose.yml
- Edit `unbound-conf/unbound.conf` as needed
- Run `docker compose up -d`
- Change your router DNS to your Pi-hole device IP Address

## Notes

- if you're not using raspberry pi, change unbound image to `mvance/unbound:latest`

## Thanks to

- Pi-hole team
- [Matthew Vance](https://github.com/MatthewVance) for unbound docker image
