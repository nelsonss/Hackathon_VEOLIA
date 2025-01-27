# Veolia EcoSentry

<img src="https://lh3.googleusercontent.com/pw/AP1GczPYmHnm995NEoitcY-pzNN5oGf5_A0Ff3w80CKhyN973-_23Rl7zbtqST3U3Xs-einmCyyTPRJYT7hQoZl-YVy7_i22RaXZ60rCaKiZe2CL_h2WTrQqxvgilXBbQlwqUEdwmctdd7XASGzijKLtbUsW7w=w864-h866-s-no-gm?authuser=0" alt="isolated"/>


**Conectando Datos, Transformando el Futuro**

---

## Índice

- [Introducción](#introducción)
- [Problema](#problema)
- [Solución: Veolia EcoSentry](#Solución-Veolia-EcoSentry)
- [Características Principales](#características-principales)
- [Beneficios](#beneficios)
- [Arquitectura Tecnológica](#arquitectura-tecnológica)
- [Guía de Instalación](#guía-de-instalación)
- [Uso](#uso)
- [Contribución](#contribución)
- [Equipo](#equipo)
- [Licencia](#licencia)
- [Contacto](#contacto)

---

## Introducción

**Veolia EcoSentry** es una plataforma integral diseñada para revolucionar la gestión de sensores y datos en Veolia. Nuestro objetivo es centralizar y simplificar la interacción con miles de sensores que operan con diversos protocolos y marcas, mejorando la eficiencia operativa y apoyando la transformación ecológica.

---

## Problema

Veolia enfrenta desafíos significativos en la gestión de datos debido a:

- **Fragmentación Tecnológica**: Múltiples sensores con protocolos incompatibles dificultan la integración y gestión eficiente.
- **Ineficiencias Operativas**: Retrasos en la recopilación y análisis de datos impactan negativamente en la toma de decisiones.
- **Dependencia de Proveedores Externos**: La necesidad constante de soporte externo aumenta los costos y reduce el control interno.
- **Riesgos de Seguridad**: Datos sensibles están expuestos debido a sistemas dispersos y falta de estandarización.

---

## Solución Veolia EcoSentry

Veolia EcoSentry aborda estos desafíos mediante:

- **Centralización de Datos**: Una plataforma única para gestionar todos los sensores y datos.
- **Integración Multiprotocolo**: Soporte para MQTT, HTTPS, MODBUS, PROFIBUS, entre otros.
- **Interfaz Intuitiva**: Diseño centrado en el usuario para facilitar la adopción y uso eficiente.
- **Seguridad Avanzada**: Protección robusta de datos sensibles.
- **Escalabilidad y Flexibilidad**: Adaptable a futuras tecnologías y necesidades.

---

## Características Principales

- **Gestión Centralizada de Sensores**: Control total sobre todos los dispositivos desde una sola plataforma.
- **Alertas y Notificaciones en Tiempo Real**: Monitoreo proactivo de eventos críticos.
- **Roles y Permisos Personalizados**: Control de acceso basado en funciones.
- **Dashboard Personalizable**: Visualizaciones y reportes adaptados a las necesidades del usuario.
- **Feedback Integrado**: Canal directo para sugerencias y reportes de los usuarios.

---

## Beneficios

- **Mejora de la Eficiencia Operativa**: Reducción significativa de tiempos y costos.
- **Decisiones Informadas**: Acceso a datos confiables en tiempo real.
- **Seguridad Reforzada**: Protección de datos críticos y cumplimiento normativo.
- **Innovación Continua**: Plataforma preparada para integrar nuevas tecnologías y funcionalidades.
- **Sostenibilidad Ambiental**: Optimización en la gestión de recursos naturales.

---

## Arquitectura Tecnológica

- **Frontend**: Angular: Framework frontend para el desarrollo de la interfaz
- **Backend**: Node.js con Express
- **Base de Datos**: PosgreSQL
- **Protocolos Soportados**: MQTT, HTTPS, MODBUS, PROFIBUS
- **Infraestructura**: Google Cloud Platform (GCP), Render
- **Seguridad**:
  - Autenticación JWT
  - Cifrado SSL/TLS

---

## Guía de Instalación

### Prerrequisitos

- **Node.js** v14 o superior
- **PostgreSQL** v16 o superior
- **Git** instalado en el sistema

### Pasos de Instalación

1. **Clonar el repositorio**

   ```bash
   git clone https://github.com/veolia/veolia-ecoSentry.git
   ```

2. **Ingresar al directorio del proyecto**

   ```bash
   cd veolia-ecoSentry
   ```

3. **Instalar dependencias del backend**

   ```bash
   cd backend
   npm install
   ```

4. **Instalar dependencias del frontend**

   ```bash
   cd ../frontend
   npm install
   ```

5. **Configurar variables de entorno**

   - Crear un archivo `.env` en los directorios `backend` y `frontend` con las variables necesarias (ver archivo `.env.example`).

6. **Iniciar la aplicación**

   - **Backend**:

     ```bash
     cd backend
     npm start
     ```

   - **Frontend**:

     ```bash
     cd frontend
     npm start
     ```

---

## Uso

1. **Acceder a la plataforma**

   - Navega a `http://localhost:3000` en tu navegador web.

2. **Crear una cuenta o iniciar sesión**

   - Regístrate con tus credenciales corporativas o inicia sesión si ya tienes una cuenta.

3. **Agregar Sensores**

   - Navega a la sección de **Sensor** y selecciona **Agregar nuevo sensor**.
   - Sigue las instrucciones para configurar el sensor según el protocolo correspondiente.

4. **Monitorear Datos**

   - Utiliza el **Dashboard** para visualizar datos en tiempo real.
   - Personaliza tus vistas y gráficos según tus necesidades.

5. **Configurar Alertas**

   - Ve a **Configuración de Alertas** para establecer umbrales y notificaciones.

---

## Contribución

¡Las contribuciones son bienvenidas! Para contribuir:

1. **Fork** del repositorio.
2. Crea una nueva **rama** con la función o corrección (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza **commits** de tus cambios (`git commit -m 'Agrega nueva funcionalidad'`).
4. **Empuja** la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un **Pull Request**.

Por favor, asegúrate de seguir las [pautas de contribución](CONTRIBUTING.md).

---

## Equipo

- **Nelson Sánchez Sánchez** - Líder de Proyecto - Analítica de Datos
- **Jerson Navarro** - Desarrollador Full Stack
- **Juan Pablo Gómez V** - Ingeniero Ambiental . Analítica de Datos


---

## Licencia

Este proyecto es propiedad de **EcoSentry** y está sujeto a acuerdos de confidencialidad y uso interno. No está disponible para distribución pública.

---

## Contacto

Para más información o soporte:

- **Email**: veolia.ecosentry@veolia.com
- **Teléfono**: +34 123 456 789
- **Sitio Web**: [www.veolia.com](https://www.veolia.com)

---

**Veolia EcoSentry** - Transformando la gestión de recursos a través de la innovación tecnológica.

---

# Anexos

## Roadmap

- **Versión 1.0**
  - Integración con protocolos adicionales (PROFIBUS, HTTPs).
  - Implementación de autenticación de dos factores.
  - Mejora de funcionalidades de reportes y análisis.

- **Versión 1.1**
  - Incorporación de inteligencia artificial para análisis predictivo.
  - Integración con sistemas heredados.
  - Optimización de rendimiento y escalabilidad.

---

## Reconocimientos

Agradecemos a todos los miembros del equipo y colaboradores que han contribuido al desarrollo de Veolia ecoSentry, así como a los usuarios piloto por su valioso feedback.

---
