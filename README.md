# Text to Speech Watson
## Config Database
Update host of datebase to your IP `localhost`

```
.
├── service
│   ├── config
│   └── database.ts 
└── 
```
Ex:
```
export const Config = {
  host:     your IP,
  port:     3306,
  username: 'root',
  password: 'password',
  database: 'app_development',
}
```
## Install docke 

` https://docs.docker.com/engine/install/ubuntu/ `

## Install docker-compose

` https://docs.docker.com/compose/install/ `

## Comands to exec docker
```
git clone https://github.com/edi2117/text_to_speech.git
cd /text_to_speech
docker-compose build
docker-compose up
```

## Access for url to navegator

### Client: "Front-end"
` 0.0.0.0:4000 `

### Service: "Back-end"
` 0.0.0.0:3000 `

### PhpMyadmin: Manager Database
`0.0.0.0:8081`

