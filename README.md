# Microservicos JAVA

## AUTH 

### Validar token 

- POST: localhost:8088/oauth/token
    `{
        authorization : {
            username: loja,
            password: lojapwd
        },
        body : {
            scope : web,
            grant_type : password,
            username : joao,
            password : joaopwd
        }
    }    
    `

# API gateway ZULL

- url: localhost:5555/actuator/routes


