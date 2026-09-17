# TryHackMe: DNS in Detail

## Conceptos Clave
- **DNS (Domain Name System):** Traduce nombres de dominio legibles por humanos a direcciones IP.
- **Jerarquía de Dominios:** TLD (.com, .org), Dominio de segundo nivel (website), Subdominio (store).

## Registros DNS
- ** A**: Direccióen IPv4
- ** AAAA**: Dirección IPv6
- ** CNAME**: Alias de un dominio a otro dominio.
- **MX**: Servidores de correo electrónico del domino e incluye una prioridad numérica para indicar a qué servidor intentar conectar primero (el de menor número tiene mayor prioridad).
- **TXT**: Campos de texto libre usados para validar la propiedad de un dominio y aplicar políticas de seguridad en el correo electrónico como SPF y DMARC para evitar sppofing o spam.
