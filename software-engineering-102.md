## Plan de Estudios Avanzado y Detallado 🧠

![Ingeniería de Software](files/software-engineering.jpeg)

¡Vamos a profundizar en el plan de estudios y a crear prompts más elaborados para que obtengas respuestas más extensas y ricas en detalles de tu asistente IA!

Este plan sigue siendo una hoja de ruta; la clave es la **práctica deliberada** y la **construcción de proyectos** cada vez más complejos. 🚀

### **Módulo 1: Fundamentos Sólidos de la Programación y Pensamiento Algorítmico**

1.  **Principios Fundamentales de la Computación y Programación:**
    * **Temas:** Evolución de los lenguajes de programación. Diferencias detalladas entre compilación e interpretación (incluyendo JIT). Paradigmas de programación: imperativo, declarativo, estructurado, orientado a objetos, funcional, y concurrente/paralelo (introducción conceptual). Abstracción, encapsulamiento, modularidad como principios. Herramientas esenciales: elección de un lenguaje robusto para aprender (Python, Java, o C# son buenas opciones), IDEs vs. editores de texto con extensiones, sistemas de control de versiones (Git).
    * **Prompt Avanzado:**
        ```
        Explícame en profundidad los distintos paradigmas de programación (imperativo, declarativo, POO, funcional, concurrente), contrastando sus filosofías, ventajas, desventajas y casos de uso típicos. ¿Cómo influye la elección de un paradigma en la estructura y mantenibilidad del software? Adicionalmente, detalla el proceso de compilación versus interpretación, incluyendo el concepto de compilación Just-In-Time (JIT) y sus beneficios.
        ```

2.  **Dominio de un Lenguaje de Programación Base (Ej. Python):**
    * **Temas:** Sintaxis avanzada: decoradores, generadores, manejo avanzado de excepciones. Tipos de datos: mutabilidad vs. inmutabilidad, colecciones especializadas (ej. `collections` en Python). Operadores: precedencia, operadores a nivel de bit. Estructuras de control: anidamiento eficiente, comprensión de listas/diccionarios.
    * **Prompt Avanzado:**
        ```
        Utilizando Python como referencia, profundiza en los tipos de datos, diferenciando claramente entre objetos mutables e inmutables y sus implicaciones en la gestión de memoria y efectos secundarios. Explica el uso avanzado de estructuras de control, incluyendo comprensiones de listas/diccionarios/conjuntos y expresiones generadoras. Detalla el manejo robusto de excepciones: jerarquía de excepciones, creación de excepciones personalizadas y el uso de bloques `try-except-else-finally`. ¿Cuáles son las buenas prácticas para escribir código Python idiomático (Pythonic)?
        ```

3.  **Funciones Avanzadas y Diseño Modular:**
    * **Temas:** Funciones de primera clase, funciones de orden superior (map, filter, reduce), clausuras (closures), decoradores (implementación y uso), recursividad avanzada (con memoización y optimización de cola si el lenguaje lo soporta), principios de diseño de funciones (cohesión, bajo acoplamiento), paso de argumentos (por valor, por referencia, por objeto/compartido). Espacios de nombres y gestión de módulos/paquetes.
    * **Prompt Avanzado:**
        ```
        Explora en detalle el concepto de funciones como ciudadanos de primera clase y funciones de orden superior, proporcionando ejemplos prácticos de `map`, `filter`, y `reduce` (o equivalentes). Desglosa el funcionamiento interno de las clausuras (closures) y los decoradores, y cómo se pueden utilizar para extender la funcionalidad de forma elegante. Discute las estrategias para optimizar la recursividad, como la memoización, y las diferencias en los mecanismos de paso de parámetros entre lenguajes (ej. paso por valor vs. paso por referencia/objeto).
        ```

4.  **Programación Orientada a Objetos (POO) en Profundidad:**
    * **Temas:** Los cuatro pilares (abstracción, encapsulamiento, herencia, polimorfismo) con ejemplos complejos. Herencia múltiple y el problema del diamante (y cómo se resuelve en diferentes lenguajes). Composición sobre herencia. Interfaces y clases abstractas. Métodos mágicos/dunder (Python), sobrecarga y anulación de métodos (override vs. overload). Principios SOLID a nivel introductorio aplicados a POO.
    * **Prompt Avanzado:**
        ```
        Profundiza en los cuatro pilares de la Programación Orientada a Objetos (Abstracción, Encapsulamiento, Herencia y Polimorfismo), detallando los beneficios y posibles inconvenientes de cada uno. Compara y contrasta herencia múltiple con interfaces y clases abstractas, discutiendo el 'problema del diamante' y sus soluciones. Argumenta cuándo es preferible la composición sobre la herencia. Finalmente, introduce los principios SOLID y cómo guían el diseño de clases robustas y mantenibles, con ejemplos de código que ilustren su aplicación.
        ```

### **Módulo 2: Dominio de Estructuras de Datos y Algoritmos (EDyA)** 🧠

1.  **Análisis de Algoritmos y Notación Asintótica:**
    * **Temas:** Notación Big O, Omega (Ω), Theta (Θ). Análisis del caso peor, mejor y promedio. Complejidad espacial. Impacto de las EDyA en la eficiencia. Amortización.
    * **Prompt Avanzado:**
        ```
        Explica de manera exhaustiva las notaciones asintóticas O, Ω y Θ, y cómo se utilizan para analizar la eficiencia de los algoritmos en términos de tiempo y espacio. Describe cómo determinar la complejidad para algoritmos iterativos y recursivos (incluyendo el teorema maestro, si es posible, de forma simplificada). Proporciona ejemplos donde la elección de una estructura de datos impacta drásticamente la complejidad de un algoritmo para un problema dado. ¿Qué es el análisis amortizado y en qué escenarios es relevante?
        ```

2.  **Estructuras de Datos Lineales Avanzadas:**
    * **Temas:** Implementación detallada de listas enlazadas (simples, dobles, circulares, con nodo fantasma). Pilas y colas: implementaciones con arrays vs. listas enlazadas, colas de prioridad (usando heaps). Deques. Casos de uso y trade-offs.
    * **Prompt Avanzado:**
        ```
        Compara y contrasta las implementaciones de pilas y colas utilizando arrays (estáticos y dinámicos) versus listas enlazadas, analizando la complejidad de sus operaciones (push, pop, enqueue, dequeue, peek) en cada caso. Profundiza en las colas de prioridad: ¿qué son, cómo se implementan eficientemente (ej. usando heaps binarios) y cuáles son sus aplicaciones críticas en sistemas operativos o algoritmos de grafos?
        ```

3.  **Estructuras de Datos No Lineales Avanzadas:**
    * **Temas:**
        * **Árboles:** Árboles binarios de búsqueda (BST) balanceados (AVL, Rojo-Negro - comprensión conceptual y de rotaciones), B-Trees y B+Trees (uso en bases de datos eSistemas de archivos). Heaps (binarios, binomiales). Tries (árboles de prefijos).
        * **Grafos:** Representaciones (matriz de adyacencia, lista de adyacencia) y sus trade-offs. Algoritmos de recorrido (BFS, DFS) y sus aplicaciones (detección de ciclos, caminos más cortos en grafos no ponderados, ordenación topológica).
        * **Tablas Hash:** Funciones hash (propiedades, colisiones), estrategias de resolución de colisiones (encadenamiento, direccionamiento abierto - sondeo lineal, cuadrático, doble hashing).
    * **Prompt Avanzado (Árboles):**
        ```
        Describe en detalle los mecanismos de autobalanceo en árboles binarios de búsqueda, enfocándote en los árboles AVL y Rojo-Negro. Explica por qué el balanceo es crucial y cómo las rotaciones ayudan a mantener la eficiencia. Además, compara los árboles B/B+ con los BST balanceados, y justifica por qué los B/B+ Trees son preferidos para el almacenamiento en disco en sistemas de bases de datos.
        ```
    * **Prompt Avanzado (Grafos):**
        ```
        Analiza las diferentes representaciones de grafos (matriz de adyacencia y lista de adyacencia), discutiendo sus implicaciones en términos de uso de memoria y eficiencia para diversas operaciones (añadir vértice/arista, comprobar adyacencia, obtener vecinos). Explica cómo los algoritmos BFS y DFS pueden adaptarse para resolver problemas como la detección de ciclos, la ordenación topológica y la búsqueda del camino más corto en grafos no ponderados.
        ```
    * **Prompt Avanzado (Tablas Hash):**
        ```
        Profundiza en el diseño de funciones hash efectivas, discutiendo propiedades deseables como la uniformidad y la eficiencia. Compara y contrasta las principales estrategias de resolución de colisiones en tablas hash (encadenamiento separado vs. direccionamiento abierto con sondeo lineal, cuadrático y doble hashing), analizando sus rendimientos y susceptibilidad a agrupamientos.
        ```

4.  **Algoritmos Fundamentales y Técnicas de Diseño:**
    * **Temas:**
        * **Ordenamiento:** Merge Sort, Quick Sort (con diferentes estrategias de pivote), Heap Sort. Análisis de estabilidad. Ordenamientos no comparativos (Counting Sort, Radix Sort).
        * **Búsqueda:** Búsqueda binaria en diferentes contextos (arrays rotados, encontrar primer/último elemento).
        * **Divide y Vencerás:** Aplicaciones más allá del ordenamiento.
        * **Programación Dinámica:** Concepto, memoización vs. tabulación. Problemas clásicos (Fibonacci, subsecuencia común más larga, problema de la mochila).
        * **Algoritmos Voraces (Greedy):** Concepto, cuándo funcionan. Problemas clásicos (cambio de monedas, problema de la mochila fraccional, Huffman).
        * **Backtracking:** Concepto. Problemas clásicos (N-Reinas, Sudoku).
    * **Prompt Avanzado (Ordenamiento):**
        ```
        Compara en detalle Quick Sort y Merge Sort, discutiendo su complejidad en el peor, mejor y caso promedio, uso de memoria (in-place vs. out-of-place) y estabilidad. Explica cómo la elección del pivote afecta el rendimiento de Quick Sort. Adicionalmente, describe el funcionamiento de Radix Sort y por qué puede superar a los algoritmos basados en comparación en ciertos escenarios.
        ```
    * **Prompt Avanzado (Programación Dinámica):**
        ```
        Explica la filosofía detrás de la Programación Dinámica, diferenciando claramente entre las técnicas de memoización (top-down) y tabulación (bottom-up). Utiliza el problema de la 'Subsecuencia Común Más Larga' (LCS) para ilustrar ambas aproximaciones, detallando la formulación de la subestructura óptima y la relación de recurrencia.
        ```
    * **Prompt Avanzado (Algoritmos Voraces):**
        ```
        Define la estrategia de algoritmos voraces (greedy) y discute las condiciones bajo las cuales un enfoque voraz puede garantizar una solución óptima (ej. propiedad de la subestructura óptima y elección voraz segura). Compara el problema de la mochila 0/1 (que requiere PD) con el problema de la mochila fraccional (resoluble con voraz) para ilustrar estas diferencias.
        ```

### **Módulo 3: Herramientas Profesionales y Flujos de Trabajo del Desarrollador** 🛠️

1.  **Maestría en Control de Versiones (Git):**
    * **Temas:** Modelo de datos de Git (blobs, trees, commits, branches como punteros). Rebase (interactivo), cherry-pick, reflog. Flujos de trabajo avanzados (GitFlow, GitHub Flow, GitLab Flow). Estrategias de merge vs. rebase. Resolución de conflictos complejos. Hooks de Git.
    * **Prompt Avanzado:**
        ```
        Desglosa el modelo de datos interno de Git (objetos blob, tree, commit y cómo se relacionan). Compara exhaustivamente las estrategias de `git merge` vs. `git rebase`, detallando sus pros, contras, cuándo usar cada una y cómo afectan el historial del proyecto. Explica el `git rebase interactivo` y cómo se utiliza para mantener un historial de commits limpio y significativo. Finalmente, describe un flujo de trabajo como GitFlow, sus ramas principales y su propósito.
        ```

2.  **Dominio de la Terminal y Scripting (Bash/PowerShell):**
    * **Temas:** Comandos avanzados (find, grep, awk, sed). Redirección y tuberías (pipes) complejas. Gestión de procesos. Variables de entorno. Escritura de scripts para automatizar tareas (backup, despliegues simples, manipulación de texto). Permisos y seguridad.
    * **Prompt Avanzado:**
        ```
        Explica cómo combinar `find`, `grep`, `awk` y `sed` con tuberías para realizar tareas complejas de búsqueda y manipulación de texto en la línea de comandos. Detalla la gestión de procesos en un entorno tipo Unix/Linux (señales, `ps`, `kill`, `jobs`, `fg`, `bg`). Proporciona un ejemplo de un script Bash o PowerShell que automatice una tarea común para un desarrollador, como la limpieza de archivos temporales o la creación de una estructura de directorios para un nuevo proyecto, explicando cada parte del script.
        ```

3.  **Entornos de Desarrollo Integrado (IDEs) y Productividad:**
    * **Temas:** Configuración avanzada de IDEs (VS Code, IntelliJ, Eclipse). Uso eficiente del depurador (breakpoints condicionales, watch expressions, call stack analysis). Herramientas de refactorización. Integración con linters y formateadores. Atajos de teclado y personalización para máxima eficiencia. Análisis estático de código.
    * **Prompt Avanzado:**
        ```
        Describe las funcionalidades avanzadas de un depurador en un IDE moderno (como VS Code o IntelliJ IDEA), incluyendo breakpoints condicionales, puntos de trace, inspección de memoria y la pila de llamadas. Explica cómo las herramientas de refactorización automática (renombrar, extraer método/variable, etc.) mejoran la calidad del código y la productividad. ¿Cómo se integran y configuran linters (ESLint, Pylint) y formateadores (Prettier, Black) para mantener un estilo de código consistente en un equipo?
        ```

### **Módulo 4: Desarrollo Backend Robusto y Escalable** ⚙️

1.  **Arquitectura Backend y APIs:**
    * **Temas:** APIs RESTful (principios, HATEOAS, versionado, idempotencia). GraphQL (introducción, diferencias con REST). gRPC (introducción). Diseño de APIs: DTOs, validación de entradas, manejo de errores consistente. Patrones de diseño para APIs. Stateless vs. stateful. Balanceo de carga y gateways de API (introducción).
    * **Prompt Avanzado:**
        ```
        Compara y contrasta en detalle los enfoques de diseño de API RESTful y GraphQL, discutiendo sus ventajas, desventajas, casos de uso ideales y cómo abordan problemas como el over-fetching y under-fetching. Explica los principios de un diseño RESTful maduro (niveles del modelo de Richardson, HATEOAS). ¿Cómo se implementa el versionado de APIs de forma efectiva y cuáles son las estrategias para manejar la evolución de una API sin romper clientes existentes?
        ```

2.  **Bases de Datos Avanzadas y Modelado:**
    * **Temas:**
        * **SQL:** Índices (B-Tree, Hash, Full-text) y optimización de consultas (EXPLAIN). Transacciones (ACID), niveles de aislamiento. Stored procedures, triggers, vistas. Replicación y sharding (conceptos).
        * **NoSQL:** Teorema CAP y sus implicaciones. Modelos de consistencia (eventual, fuerte). Diseño de esquemas para bases de datos documentales (MongoDB), clave-valor (Redis), columnares (Cassandra). Casos de uso avanzados para cada tipo.
        * **ORMs/ODMs:** Funcionamiento interno, pros y contras, problema N+1.
    * **Prompt Avanzado (SQL):**
        ```
        Profundiza en las propiedades ACID de las transacciones en bases de datos relacionales y explica los diferentes niveles de aislamiento de transacción (Read Uncommitted, Read Committed, Repeatable Read, Serializable) y los fenómenos que previenen (lecturas sucias, no repetibles, fantasma). Describe cómo funcionan los índices B-Tree a bajo nivel y cómo utilizar la sentencia `EXPLAIN` para analizar y optimizar consultas SQL complejas.
        ```
    * **Prompt Avanzado (NoSQL):**
        ```
        Explica el Teorema CAP (Consistencia, Disponibilidad, Tolerancia a Particiones) y cómo influye en el diseño de sistemas distribuidos y la elección de bases de datos NoSQL. Compara los modelos de consistencia (desde eventual hasta fuerte) y discute los trade-offs. Para una base de datos documental como MongoDB, describe estrategias de modelado de datos, incluyendo embedding vs. referencing, y cuándo usar cada una.
        ```
    * **Prompt Avanzado (ORMs/ODMs):**
        ```
        Analiza críticamente el uso de Object-Relational Mappers (ORMs) y Object-Data Mappers (ODMs). Describe sus ventajas (productividad, abstracción de BD) y desventajas (posible sobrecarga, consultas ineficientes, el problema de 'N+1 selects'). ¿Cómo se puede mitigar el problema N+1 y cuándo podría ser preferible escribir SQL/consultas nativas directamente?
        ```

3.  **Frameworks Backend y Desarrollo de Servicios:**
    * **Temas:** (Ej. Django/Flask/FastAPI en Python, Spring Boot en Java, Express/NestJS en Node.js). Arquitectura interna del framework (Middleware, request lifecycle). Inyección de dependencias. Patrones de diseño comunes en frameworks (MVC, MVT, etc.). Creación de microservicios (principios, comunicación inter-servicio: síncrona vs. asíncrona con colas de mensajes).
    * **Prompt Avanzado (Ej. con Spring Boot):**
        ```
        Describe la arquitectura de Spring Boot, incluyendo el papel del contenedor de Inversión de Control (IoC), la inyección de dependencias y el sistema de auto-configuración. Explica cómo se maneja el ciclo de vida de una petición HTTP, incluyendo el papel de los DispatcherServlet, controllers, services y repositories. ¿Cómo facilita Spring Boot la creación de APIs RESTful y la integración con bases de datos (JPA/Hibernate) y sistemas de mensajería (Kafka/RabbitMQ)?
        ```

4.  **Seguridad en Backend y Autenticación/Autorización Avanzada:**
    * **Temas:** OAuth 2.0 y OpenID Connect (flujos detallados). JWT (estructura, firma, validación, almacenamiento seguro, revocación). RBAC y ABAC. Prevención de ataques comunes (OWASP Top 10 detallado: Inyección SQL, XSS, CSRF, SSRF, etc.). HTTPS y TLS. Gestión de secretos.
    * **Prompt Avanzado:**
        ```
        Detalla los diferentes flujos (grant types) de OAuth 2.0 (Authorization Code, Implicit, Client Credentials, Password Credentials) explicando sus casos de uso, actores involucrados y consideraciones de seguridad. Profundiza en la estructura de un JSON Web Token (JWT), cómo se firman y validan, y las estrategias para su almacenamiento seguro en el cliente y su revocación. Compara Role-Based Access Control (RBAC) con Attribute-Based Access Control (ABAC) en términos de flexibilidad y gestión.
        ```

### **Módulo 5: Desarrollo Frontend Moderno y Experiencia de Usuario (UX)** 🖥️

1.  **HTML Semántico y Accesibilidad (A11Y):**
    * **Temas:** Estándares WAI-ARIA. Uso correcto de roles y atributos ARIA. Navegación por teclado. Contraste de color. HTML semántico para SEO y accesibilidad. Testeo de accesibilidad.
    * **Prompt Avanzado:**
        ```
        Explica la importancia de la accesibilidad web (A11Y) y cómo los estándares WAI-ARIA ayudan a crear experiencias inclusivas. Describe al menos cinco atributos ARIA comunes, su propósito y cómo implementarlos correctamente. ¿Qué herramientas y técnicas se pueden usar para auditar y mejorar la accesibilidad de un sitio web, incluyendo la navegación por teclado y el contraste de color?
        ```

2.  **CSS Avanzado, Arquitecturas CSS y Preprocesadores:**
    * **Temas:** Especificidad y cascada a fondo. Custom Properties (variables CSS). Arquitecturas CSS (BEM, SMACSS, ITCSS). Preprocesadores (Sass/SCSS en detalle: mixins, funciones, herencia, módulos). CSS-in-JS (introducción). Optimización de rendimiento CSS.
    * **Prompt Avanzado:**
        ```
        Compara y contrasta las metodologías de arquitectura CSS como BEM, SMACSS e ITCSS, discutiendo sus objetivos, ventajas y cómo ayudan a gestionar la especificidad y mantenibilidad en proyectos grandes. Profundiza en las características avanzadas de Sass/SCSS, como mixins con argumentos, funciones personalizadas, y el uso de `@use` y `@forward` para la modularización. ¿Cómo impactan las Custom Properties de CSS en la tematización y la interactividad?
        ```

3.  **JavaScript Profundo y Asincronía en el Navegador:**
    * **Temas:** Event Loop, Call Stack, Task Queue, Microtask Queue (diferencias y prioridades). Promesas (creación, encadenamiento, `Promise.all`, `Promise.race`). `async/await` (manejo de errores). Generadores e iteradores. Módulos ES6. Web Workers para concurrencia. APIs del navegador (Fetch avanzada, WebSockets, LocalStorage/SessionStorage/IndexedDB). Gestión de memoria y garbage collection (conceptos).
    * **Prompt Avanzado:**
        ```
        Desglosa el funcionamiento del Event Loop en JavaScript, explicando la interacción entre el Call Stack, la Task Queue (o Macrotask Queue) y la Microtask Queue. ¿Cómo afecta esta arquitectura al manejo de operaciones asíncronas y al renderizado de la UI? Profundiza en el manejo de errores con `async/await` y `Promise.catch()`, y discute patrones para gestionar múltiples promesas concurrentes (`Promise.all`, `Promise.allSettled`, `Promise.race`). Introduce el concepto de Web Workers y cuándo son útiles.
        ```

4.  **Frameworks/Librerías Frontend Modernas (Ej. React, Vue, Angular):**
    * **Temas:** (Elegir uno y profundizar) Gestión de estado avanzada (Redux, Vuex, NgRx, Zustand, Context API con optimizaciones). Patrones de componentes (Higher-Order Components, Render Props, Hooks en React). Enrutamiento avanzado (rutas protegidas, lazy loading). Optimización de rendimiento (memoization, virtual DOM diffing, tree shaking, code splitting). Server-Side Rendering (SSR) y Static Site Generation (SSG) (conceptos y beneficios). Testing de componentes.
    * **Prompt Avanzado (Ej. con React y Redux/Zustand):**
        ```
        Explica en detalle la necesidad de bibliotecas de gestión de estado global como Redux o Zustand en aplicaciones React complejas. Compara sus arquitecturas (principios de Redux: single source of truth, state is read-only, changes are made with pure functions vs. la simplicidad de Zustand). Describe patrones avanzados para la composición de componentes, como Higher-Order Components (HOCs) y Render Props, y cómo los Hooks (ej. `useContext`, `useReducer`, custom hooks) han influido en estos patrones. ¿Cómo se implementa el 'code splitting' y 'lazy loading' de rutas para mejorar el rendimiento inicial de la aplicación?
        ```

### **Módulo 6: Principios, Patrones y Prácticas de Ingeniería de Software de Alto Nivel** 🏗️

1.  **Principios de Diseño de Software y Arquitectura Limpia:**
    * **Temas:** Principios SOLID en profundidad con ejemplos y anti-ejemplos. DRY, KISS, YAGNI. Law of Demeter. Tell, Don't Ask. Principios de Package/Component Design (REP, CCP, CRP, ADP, SDP, SAP). Introducción a la Arquitectura Limpia (Clean Architecture) o Arquitectura Hexagonal.
    * **Prompt Avanzado:**
        ```
        Para cada uno de los principios SOLID, proporciona una definición clara, un ejemplo de código que viole el principio y cómo refactorizarlo para cumplirlo, explicando los beneficios obtenidos. Adicionalmente, introduce los principios de diseño de componentes de Robert C. Martin (ej. REP, CCP, CRP) y cómo guían la cohesión y el acoplamiento entre módulos. ¿Cómo se relacionan estos principios con conceptos de Arquitectura Limpia o Hexagonal?
        ```

2.  **Patrones de Diseño GoF y Arquitectónicos:**
    * **Temas:**
        * **Creacionales:** Factory Method, Abstract Factory, Builder, Prototype, Singleton (y sus problemas).
        * **Estructurales:** Adapter, Bridge, Composite, Decorator, Facade, Flyweight, Proxy.
        * **Comportamiento:** Chain of Responsibility, Command, Interpreter, Iterator, Mediator, Memento, Observer, State, Strategy, Template Method, Visitor.
        * **Patrones Arquitectónicos:** MVC, MVP, MVVM, Microservicios, Event-Driven, CQRS, Event Sourcing (introducción).
    * **Prompt Avanzado (Patrones GoF):**
        ```
        Elige tres patrones de diseño del GoF de diferentes categorías (creacional, estructural, comportamiento). Para cada uno: a) Describe el problema que resuelve y su intención. b) Dibuja una estructura UML básica. c) Proporciona un ejemplo de código conceptual en un lenguaje de tu elección. d) Discute sus ventajas, desventajas y escenarios de aplicación típicos. ¿Existen anti-patrones o usos incorrectos comunes para estos patrones?
        ```
    * **Prompt Avanzado (Patrones Arquitectónicos):**
        ```
        Compara y contrasta los patrones arquitectónicos MVC, MVP y MVVM, destacando cómo gestionan la separación de responsabilidades y el flujo de datos entre la interfaz de usuario, la lógica de negocio y los datos. Adicionalmente, introduce el patrón CQRS (Command Query Responsibility Segregation) y explica cómo puede combinarse con Event Sourcing para construir sistemas reactivos y auditables.
        ```

3.  **Testing Avanzado y Calidad de Software:**
    * **Temas:** Pirámide de testing (énfasis en unit e integration). Mocking, stubbing, fakes, spies. Test Doubles. Cobertura de código (statement, branch, path) y sus limitaciones. TDD y BDD en la práctica. Pruebas de mutación. Pruebas de propiedad (Property-based testing). Pruebas de performance y carga (introducción).
    * **Prompt Avanzado:**
        ```
        Explica en profundidad la diferencia entre mocks, stubs, fakes y spies (Test Doubles), proporcionando ejemplos de cuándo y cómo usar cada uno en pruebas unitarias y de integración. Discute la importancia y las limitaciones de las métricas de cobertura de código. Describe cómo se implementa el ciclo TDD (Red-Green-Refactor) en la práctica y cómo BDD (usando herramientas como Cucumber/Gherkin) puede mejorar la colaboración entre desarrolladores y stakeholders. Introduce el concepto de 'Property-Based Testing' y sus ventajas sobre el testing basado en ejemplos.
        ```

### **Módulo 7: DevOps, Cloud y Operaciones Modernas** ☁️🐳

1.  **Cultura DevOps, CI/CD y Automatización:**
    * **Temas:** Principios de DevOps (CAMS). Pipelines de CI/CD (construcción, pruebas, despliegue). Herramientas (Jenkins, GitLab CI, GitHub Actions). Monitoreo y logging en CI/CD. Infrastructure as Code (IaC) con Terraform o Pulumi (introducción). Gestión de configuración (Ansible).
    * **Prompt Avanzado:**
        ```
        Describe en detalle las fases típicas de un pipeline de Integración Continua y Despliegue Continuo (CI/CD), desde el commit de código hasta el despliegue en producción. Explica el concepto de 'Infrastructure as Code' (IaC) y cómo herramientas como Terraform permiten gestionar la infraestructura de forma declarativa y versionable. ¿Cómo se integra la gestión de configuración con Ansible en un pipeline de CI/CD para asegurar la consistencia de los entornos?
        ```

2.  **Contenedores y Orquestación:**
    * **Temas:** Docker (Dockerfile, images, containers, volumes, networking). Docker Compose para entornos locales. Kubernetes (arquitectura: Master/Nodes, Pods, Services, Deployments, Ingress, ConfigMaps, Secrets). Helm para gestión de paquetes en Kubernetes. Service Mesh (Istio, Linkerd - introducción).
    * **Prompt Avanzado:**
        ```
        Explica la arquitectura fundamental de Kubernetes, detallando el rol de los componentes del Master (API Server, etcd, Scheduler, Controller Manager) y los Nodos (Kubelet, Kube-proxy, Container Runtime). Describe los objetos clave como Pods, Services, Deployments e Ingress, y cómo interactúan para desplegar y exponer una aplicación escalable. ¿Qué problemas resuelve un Service Mesh como Istio en un entorno de microservicios desplegado en Kubernetes?
        ```

3.  **Cloud Computing Avanzado (AWS, Azure o GCP):**
    * **Temas:** (Elegir un proveedor y profundizar)
        * **Compute:** VMs, Contenedores gestionados (ECS, EKS, AKS, GKE), Serverless (Lambda, Azure Functions, Cloud Functions).
        * **Storage:** Object storage (S3, Blob Storage, GCS), Block storage, File storage.
        * **Databases:** RDS, Aurora, Cosmos DB, Spanner, DynamoDB, Cloud SQL.
        * **Networking:** VPCs, subnets, security groups, load balancers.
        * **IAM:** Roles, políticas, usuarios, grupos.
        * **Monitoring y Logging:** CloudWatch, Azure Monitor, Google Cloud's operations suite.
        * **Diseño para la nube:** Escalabilidad, resiliencia (multi-AZ, multi-región), optimización de costes.
    * **Prompt Avanzado (Ej. con AWS):**
        ```
        Compara y contrasta los servicios de cómputo de AWS: EC2, ECS (con Fargate) y Lambda, discutiendo sus modelos de facturación, escalabilidad, gestión y casos de uso ideales. Explica cómo diseñar una arquitectura de aplicación web de tres capas (web, app, base de datos) altamente disponible y escalable en AWS utilizando servicios como Application Load Balancer, Auto Scaling Groups, RDS Multi-AZ y S3 para contenido estático. ¿Cómo se utiliza IAM para implementar el principio de mínimo privilegio en esta arquitectura?
        ```

4.  **Observabilidad y Monitoreo en Producción:**
    * **Temas:** Los tres pilares de la observabilidad: logs, métricas, traces. Herramientas de monitoreo (Prometheus, Grafana, Datadog, New Relic). Alertas efectivas. Análisis de causa raíz (RCA). SLOs, SLAs, SLIs.
    * **Prompt Avanzado:**
        ```
        Define los tres pilares de la observabilidad (logs, métricas y traces) y cómo cada uno contribuye a entender el comportamiento de un sistema en producción. Explica cómo herramientas como Prometheus y Grafana pueden usarse para recolectar métricas y visualizarlas. Describe el proceso de definir Service Level Objectives (SLOs), Service Level Agreements (SLAs) y Service Level Indicators (SLIs) y cómo se utilizan para guiar las decisiones de ingeniería y operaciones.
        ```