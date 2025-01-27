# Veolia EcoSentry

<img src="https://lh3.googleusercontent.com/pw/AP1GczPYmHnm995NEoitcY-pzNN5oGf5_A0Ff3w80CKhyN973-_23Rl7zbtqST3U3Xs-einmCyyTPRJYT7hQoZl-YVy7_i22RaXZ60rCaKiZe2CL_h2WTrQqxvgilXBbQlwqUEdwmctdd7XASGzijKLtbUsW7w=w864-h866-s-no-gm?authuser=0" alt="isolated"/>


# Veolia EcoSentry 
**Connecting Data, Transforming the Future**

## Table of Contents
1. [Introduction](#introduction)
2. [Problem](#problem)
3. [Solution: Veolia EcoSentry](#solution-veolia-ecosentry)
4. [Key Features](#key-features)
5. [Benefits](#benefits)
6. [Technological Architecture](#technological-architecture)
7. [Installation Guide](#installation-guide)
8. [Usage](#usage)
9. [Contributing](#contributing)
10. [Team](#team)
11. [License](#license)
12. [Contact](#contact)
13. [Annexes](#annexes)

---

## Introduction
**Veolia EcoSentry** is a comprehensive platform designed to revolutionize the management of sensors and data for Veolia. Our goal is to centralize and simplify the interaction with thousands of sensors operating under various protocols and brands, improving operational efficiency and driving ecological transformation.

---

## Problem
Veolia faces significant challenges in data management due to:

- **Technological Fragmentation**: Multiple sensors with incompatible protocols hinder efficient integration and management.  
- **Operational Inefficiencies**: Delays in data collection and analysis negatively impact decision-making.  
- **Dependency on External Providers**: Continuous reliance on external support raises costs and reduces internal control.  
- **Security Risks**: Sensitive data is exposed due to dispersed systems and lack of standardization.

---

## Solution: Veolia EcoSentry
**Veolia EcoSentry** addresses these challenges by providing:

- **Data Centralization**: A single platform to manage all sensors and data.  
- **Multi-Protocol Integration**: Support for MQTT, HTTPS, MODBUS, PROFIBUS, among others.  
- **Intuitive Interface**: User-centered design for easy adoption and efficient usage.  
- **Advanced Security**: Robust protection for sensitive data.  
- **Scalability and Flexibility**: Adaptable to future technologies and requirements.

---

## Key Features
- **Centralized Sensor Management**: Complete control of all devices from one platform.  
- **Real-Time Alerts and Notifications**: Proactive monitoring of critical events.  
- **Custom Roles and Permissions**: Role-based access control.  
- **Customizable Dashboard**: Personalized views and reports tailored to user needs.  
- **Built-In Feedback**: Direct channel for user suggestions and reports.

---

## Benefits
- **Improved Operational Efficiency**: Significant reduction in time and cost.  
- **Informed Decision-Making**: Access to reliable real-time data.  
- **Enhanced Security**: Protection of critical data and regulatory compliance.  
- **Continuous Innovation**: A platform ready to integrate new technologies and features.  
- **Environmental Sustainability**: Optimized management of natural resources.

---

## Technological Architecture
- **Frontend**: [Angular](https://angular.io/)  
- **Backend**: [Node.js](https://nodejs.org/) with [Express](https://expressjs.com/)  
- **Database**: PostgreSQL  
- **Supported Protocols**: MQTT, HTTPS, MODBUS, PROFIBUS  
- **Infrastructure**: Google Cloud Platform (GCP) and Render  
- **Security**:  
  - JWT Authentication  
  - SSL/TLS Encryption  

---

## Installation Guide

### Prerequisites
- **Node.js** v14 or higher  
- **PostgreSQL** v16 or higher  
- **Git** installed on your system

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/veolia/veolia-ecoSentry.git


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
