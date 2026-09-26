# Ventajas y desventajas de los tipos de criptografía

<table>
  <thead>
    <tr>
      <th>TIPO</th>
      <th>VENTAJAS</th>
      <th>DESVENTAJS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Criptografía simétrica</td>
      <td>Muy rápida, eficiente con grandes cantidades de datos y requiere menos recursos.</td>
      <td>Requiere compartir la clave secreta de forma segura; administrar muchas claves puede ser complicado.</td>
    </tr>
    <tr>
      <td>Criptografía asimétrica</td>
      <td>Permite comunicación segura sin compartir previamente una clave secreta; permite firmas digitales.</td>
      <td>Es más lenta y consume más recursos.</td>
    </tr>
    <tr>
      <td>Criptografía híbrida</td>
      <td>Combina la velocidad de la simétrica con la seguridad de la asimétrica.</td>
      <td>Es más compleja de implementar.</td>
    </tr>
    <tr>
      <td>Funciones hash criptográficas</td>
      <td>Muy rápida; permite verificar integridad.</td>
      <td>No permite recuperar el mensaje original; algunos algoritmos antiguos son inseguros.</td>
    </tr>
    <tr>
      <td>Códigos de autenticación de mensajes (MAC)</td>
      <td>Garantiza autenticidad e integridad.</td>
      <td>Requiere que las partes compartan una clave secreta.</td>
    </tr>
    <tr>
      <td>Firmas digitales</td>
      <td>Verifican autenticidad e integridad de documentos/mensajes.</td>
      <td>Requieren gestión de claves y pueden ser costosas computacionalmente.</td>
    </tr>
    <tr>
      <td>Criptografía autenticada (AEAD)</td>
      <td>Cifra y autentica los datos simultáneamente.</td>
      <td>Una mala gestión de nonces/IV puede comprometer la seguridad.</td>
    </tr>
    <tr>
      <td>Criptografía de curva elíptica (ECC)</td>
      <td>Ofrece alta seguridad con claves pequeñas.</td>
      <td>Su implementación es compleja y requiere parámetros adecuados.</td>
    </tr>
    <tr>
      <td>Criptografía poscuántica (PQC)</td>
      <td>Diseñada para resistir ataques de computadores cuánticos.</td>
      <td>Algunos algoritmos</td>
    </tr>
    <tr>
      <td>Criptografía basada en retículas</td>
      <td>Buena candidata para sistemas poscuánticos y permite construcciones avanzadas.</td>
      <td>Puede requerir más almacenamiento y procesamiento.</td>
    </tr>
    <tr>
      <td>Criptografía basada en códigos</td>
      <td>Tiene muchos años de investigación y resistencia potencial a ataques cuánticos.</td>
      <td>Algunos esquemas necesitan claves públicas enormes.</td>
    </tr>
    <tr>
      <td>Criptografía basada en hashes</td>
      <td>Se basa en funciones hash bien estudiadas y puede resistir ataques cuánticos.</td>
      <td>Las firmas pueden ser grandes y requerir más operaciones.</td>
    </tr>
    <tr>
      <td>Criptografía basada en emparejamiento</td>
      <td>Permite sistemas avanzados como firmas agregadas.</td>
      <td>Los cálculos son complejos y pueden ser costosos.</td>
    </tr>
    <tr>
      <td>Criptografía basada en isogenias</td>
      <td>Puede ofrecer construcciones con claves relativamente pequeñas.</td>
      <td>Algunos enfoques han sido vulnerados y actualmente es un área de investigación.</td>
    </tr>
    <tr>
      <td>Criptografía homomórfica</td>
      <td>Permite procesar determinados datos sin descifrarlos.</td>
      <td>Es muy lenta y requiere muchos recursos.</td>
    </tr>
    <tr>
      <td>Criptografía de umbral</td>
      <td>Distribuye una clave o capacidad entre varias personas.</td>
      <td>Requiere coordinación entre múltiples participantes.</td>
    </tr>
    <tr>
      <td>Secret Sharing</td>
      <td>Permite dividir un secreto entre varias personas para aumentar la seguridad.</td>
      <td>Perder suficientes partes puede impedir recuperar el secreto.</td>
    </tr>
    <tr>
      <td>Computación multipartita segura (MPC)</td>
      <td>Permite realizar cálculos conjuntos sin revelar todos los datos privados.</td>
      <td>Puede requerir mucha comunicación y procesamiento.</td>
    </tr>
    <tr>
      <td>Pruebas de conocimiento cero (ZKP)</td>
      <td>Permite demostrar algo sin revelar el secreto correspondiente.</td>
      <td>Puede ser complejo y costoso computacionalmente.</td>
    </tr>
    <tr>
      <td>Firmas de anillo</td>
      <td>Ocultan cuál miembro del grupo realizó una firma.</td>
      <td>Las firmas pueden ser más grandes y complicar auditorías.</td>
    </tr>
    <tr>
      <td>Firmas agregadas</td>
      <td>Varias firmas pueden combinarse en una sola, reduciendo datos.</td>
      <td>Requieren protocolos y algoritmos especializados.</td>
    </tr>
    <tr>
      <td>Criptografía funcional</td>
      <td>Permite controlar qué información puede obtenerse de datos cifrados.</td>
      <td>Es compleja y puede ser costosa computacionalmente.</td>
    </tr>
    <tr>
      <td>Criptografía cuántica</td>
      <td>Aprovecha propiedades cuánticas para determinadas tareas de seguridad.</td>
      <td>Requiere hardware especializado y puede ser costosa.</td>
    </tr>
    <tr>
      <td>Criptografía basada en identidad</td>
      <td>Puede utilizar identificadores como correos electrónicos dentro del sistema de claves.</td>
      <td>Requiere una autoridad de confianza que gestione claves maestras.</td>
    </tr>
    <tr>
      <td>Criptografía basada en atributos</td>
      <td>Permite controlar acceso según características o permisos del usuario.</td>
      <td>La administración de atributos y revocaciones puede ser compleja.</td>
    </tr>
    <tr>
      <td>Criptografía visual</td>
      <td>Puede representar secretos mediante imágenes o partes visuales.</td>
      <td>Tiene aplicaciones limitadas y puede requerir varias partes.</td>
    </tr>
    <tr>
      <td>Criptografía ligera (Lightweight Cryptography)</td>
      <td>Diseñada para dispositivos con poca memoria, energía y procesamiento.</td>
      <td>Tiene que equilibrar cuidadosamente seguridad, rendimiento y recursos.</td>
    </tr>
    <tr>
      <td>Criptografía de búsqueda (Searchable Encryption)</td>
      <td>Permite realizar determinadas búsquedas sobre datos cifrados.</td>
      <td>Puede revelar ciertos patrones de acceso y ser más lenta.</td>
    </tr>
    <tr>
      <td>Criptografía denegable (Deniable Encryption)</td>
      <td>Puede proporcionar negación plausible sobre determinados datos cifrados.</td>
      <td>Es compleja y no funciona de la misma manera en todos los escenarios.</td>
    </tr>
    <tr>
      <td>Criptografía basada en tokens</td>
      <td>Facilita autenticación y control de acceso mediante tokens.</td>
      <td>La seguridad depende de proteger, expirar y revocar correctamente los tokens.</td>
    </tr>
  </tbody>
</table>
