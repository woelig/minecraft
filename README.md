# Java and Bedrock Minecraft Server
My flavor of a fully functional Java and Bedrock Minecraft server. With plugin controller, CLI access, updates are simple (just restart the container) and can be used to host large worlds. The mobs are also a bit more difficult 😉. I did spend some time working out the kinks for this image and hope it helps someone else who wants to do the same thing. Enjoy!

## Using `docker-compose`

1. Install Docker

	- [Docker Install documentation](https://docs.docker.com/install/)
	- [Docker-Compose Install documentation](https://docs.docker.com/compose/install/)

2. Clone the main branch of the [repository](https://github.com/woelig/minecraft)

	```bash
	cd /opt
	git clone https://github.com/woelig/minecraft
	cd minecraft
	```

3. Bring up your stack by running

	```bash
	docker-compose up -d
	```
	
4. Configure the plugins (URLS are in the docker-compose.yml)