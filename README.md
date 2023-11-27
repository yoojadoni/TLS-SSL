# TLS-SSL
spring boot에서 ssl 로그확인방법

-Djavax.net.debug=ssl:handshake

application.yml(properties)
logging:
  level:
    net: DEBUG
    javax: DEBUG
   
