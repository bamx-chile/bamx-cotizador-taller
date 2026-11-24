# BAMX Cotizador Taller

Cotizador web para talleres mecánicos. El cliente elige la categoría de su
vehículo y el servicio, y recibe un presupuesto con precio base, recargo por
dificultad y recargo por espera de repuestos.

> 🚧 En desarrollo, parte del camino **Road a Freelancer** de BAMX.

## Cómo se calcula el precio
Precio Base (servicio + categoría) + espera de repuestos (se realiza un cobro si la reparacion pasa de 1 semana a la espera de repuestos) + horas extra por dificultad (se estipula un valor general de la hora, se evalua entorno a la dificultad de cambiar o remover piezas(tornillo agripados, desmonte extra partes, etc)) + repuestos (opcional si el cliente los trae o nosotros los compramos)

## Stack
C# · ASP.NET Core · Entity Framework Core · Azure SQL · JavaScript · Azure App Service

## Estado
- [ ] Modelo de datos
- [ ] API de cotización
- [ ] Interfaz web
- [ ] Despliegue en Azure

## Lo que estoy aprendiendo
-Modelo de datos:
  .....

## Autor
Branko Alvarez · [LinkedIn](https://www.linkedin.com/in/brankoalvarez/) · [TikTok](https://www.tiktok.com/@bamx.chile)
