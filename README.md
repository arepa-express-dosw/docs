# Arepa Express · Documentación y Evidencias de Laboratorio

Repositorio central de documentación, informe técnico y evidencias del laboratorio **Arepa Express: API Gateway y RabbitMQ en Azure** (DOSW, Semana 14).

## Estructura del repositorio

```text
docs/
├── README.md               # Descripción general y enlaces a servicios
├── informe-laboratorio.md  # Informe técnico con explicaciones, capturas y experimentos
└── capturas/               # Carpeta con las evidencias fotográficas del despliegue
```

## Repositorios del proyecto

- [menu-service](https://github.com/arepa-express-dosw/menu-service): Catálogo de arepas y precios (`GET /menu`).
- [pedidos-service](https://github.com/arepa-express-dosw/pedidos-service): Recepción de pedidos y publicación de eventos (`POST /pedidos`).
- [cocina-service](https://github.com/arepa-express-dosw/cocina-service): Consumidor asíncrono (`cocina.pedidos`).
- [notificaciones-service](https://github.com/arepa-express-dosw/notificaciones-service): Consumidor asíncrono (`notificaciones.pedidos`).

