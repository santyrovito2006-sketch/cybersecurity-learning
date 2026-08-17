# Fundamentos de ciberseguridad

## CIA Triad

La CIA Triad resume tres objetivos básicos de seguridad:

- **Confidentiality:** que la información solo pueda ser vista por personas autorizadas.
- **Integrity:** que los datos no sean modificados de forma no autorizada.
- **Availability:** que sistemas y datos estén disponibles cuando se necesiten.

## Amenaza, vulnerabilidad y riesgo

Una **amenaza** es algo que puede causar daño. Una **vulnerabilidad** es una debilidad que puede ser aprovechada. El **riesgo** aparece cuando existe la posibilidad de que una amenaza explote una vulnerabilidad y genere impacto.

Ejemplo: un servidor sin parches tiene una vulnerabilidad. Un atacante que busca explotarla representa una amenaza. La posibilidad de que lo consiga y afecte al negocio es el riesgo.

## Controles de seguridad

Los controles buscan reducir riesgos. Pueden ser:

- **Preventivos:** intentan evitar que ocurra el incidente.
- **Detectivos:** ayudan a descubrir actividad sospechosa.
- **Correctivos:** ayudan a recuperar o corregir después de un incidente.

También pueden clasificarse como administrativos, técnicos o físicos.

## Defense in Depth

La defensa en profundidad consiste en no depender de una sola protección. Se combinan distintas capas, por ejemplo:

firewall → autenticación → permisos → EDR → monitoreo → backups

Si una capa falla, todavía quedan otras barreras.

## Mitigación y detección

No todas las medidas evitan completamente un ataque. Algunas reducen la probabilidad y otras permiten detectarlo rápido.

Ejemplos:

- capacitación anti-phishing → mitigación humana
- patch management → mitigación técnica
- reglas SIEM → detección
- EDR → detección y respuesta
