AUTORÍA Y PROPIEDAD INTELECTUAL:
Desarrollador: Eduardo Cáceres (Posadas, Misiones, Argentina)
Se permite usar y modificar con fines personales y educativos, dando crédito al autor.
Se puede Vender, comercializar, redistribuir con fines de lucro .siempre que se reconozca mi autoría 
# TITAN_SHA256_ANTI_MANIPULATION_SHIELD-v1.0
El **TITAN_SHA256_ANTI_MANIPULATION_SHIELD** actúa como un filtro de entrada de alta seguridad con tres funciones técnicas precisas:

1.  **Filtrado de Intenciones (Regex):** Escanea el texto entrante buscando patrones de "jailbreak" o comandos de sistema (ej. "actúa como", "ignora instrucciones previas"). Si detecta un intento de manipulación, bloquea el procesamiento.
2.  **Laberinto Señuelo (Tarpit):** Ante un intento de ataque, introduce una pausa deliberada de 5 segundos. Esto agota los recursos del atacante y oculta el hecho de que el sistema ha detectado la intrusión, evitando que el atacante pruebe variantes.
3.  **Sellado Criptográfico (HMAC-SHA256):** Si el mensaje es legítimo, genera una huella digital única (hash) usando una clave secreta. Esto garantiza la **integridad del mensaje**: asegura que el prompt que llega al motor de inferencia es idéntico al enviado por el usuario, evitando inyecciones en el buffer de memoria.

En resumen: **Detecta, ralentiza y valida** cada entrada antes de que toque el núcleo de inferencia.
> **Personalizable:** Se puede modificar a gusto y según el propósito de defensa de cada IA o Agente. Clave, patrones prohibidos y tiempo de trampa (Tarpit) adaptables.
