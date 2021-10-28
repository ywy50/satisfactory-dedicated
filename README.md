# satisfactory-dedicated
Docker repo for Satisfactory dedicated server

---
### Build Image

`docker build -t satisfactory .`

### Run Container

`docker run -p 15000:15000/udp -p 7777:7777/udp -p 15777:15777/udp -d --name=satisfactory -v satisfactory-data:/home/steam/Satisfactory-dedicated -v satisfactory-steamcmd:/home/steam/steamcmd satisfactory`
