# Human chat

### ¿ Como funciona ?

Human chat es un proyecto que funciona mediante un websocket que ha sido programado con el marco de trabajo con springboot apoyandose de STOMP (simple text-oriented messaging protocol)

### Funcionamiento
![websocket example on server](https://user-images.githubusercontent.com/82422683/175851057-e1b3ece0-d90e-4774-a0eb-308c8086b3f2.png)

---

### ¿Que es Stomp ?
A resumidas cuentas podríamos decir que STOMP es una especie de sobre que mediante un payload ayuda a la comunicación desde el servidor.

> Librería nativa de Spring framework

``` Java
import org.springframework.web.socket.config.annotation.StompEndpointRegistry;
```
### Funcionamiento

![websocket_back_STOMPIMG](https://user-images.githubusercontent.com/82422683/175853257-ab0e03e3-7e40-4a99-9444-45c029d878b7.png)

---


