# TP Turnera Médica 🏥

Turnera médica desarrollada en **Java**, con base de datos embebida **H2**, como trabajo final.

---

## 📌 Índice

* [Descripción del proyecto](#descripción-del-proyecto)
* [Características](#características)
* [Tecnologías usadas](#tecnologías-usadas)
* [Instalación y ejecución local](#instalación-y-ejecución-local)
* [Estructura del proyecto](#estructura-del-proyecto)
* [Pruebas / casos de uso](#pruebas--casos-de-uso)
* [Mejoras posibles](#mejoras-posibles)
* [Autor](#autor)

---

## 🧩 Descripción del proyecto

Este proyecto es una **turnera médica**: permite gestionar turnos, pacientes y médicos. La idea es servir como backend (y parte de interfaz) para una aplicación de gestión de turnos en un entorno clínico o consultorio.
La base de datos elegida es H2, lo que facilita que el proyecto funcione “out of the box” sin depender de motores externos.

---

## ✅ Características

* Registro y autenticación de usuarios (médicos, pacientes)
* Gestión de turnos: creación, modificación, cancelación
* Asociación entre pacientes y médicos
* Persistencia de datos en H2
* Posible interfaz (según tu implementación) para consultar turnos
* Lógica de negocio clara y modular

---

## 🛠️ Tecnologías usadas

* **Java** (versión según tu proyecto)
* **H2 Database**
* (Opcional, si lo usás) algún framework web (Spring, etc.)
* Herramientas de compilación / gestión (Maven, Gradle o similar)
* Estructura de paquetes estándar

---

## 🚀 Instalación y ejecución local

Estas instrucciones asumen que tenés Java instalado en tu máquina.

1. Clonar este repo

   ```bash
   git clone https://github.com/PRodri57/TP-Turnera-Medica.git
   cd TP-Turnera-Medica
   ```
2. Construir el proyecto (ajustá según tu herramienta, por ejemplo Maven o Gradle)

   ```bash
   mvn clean install
   ```

   o

   ```bash
   gradle build
   ```
3. Ejecutar la aplicación

   ```bash
   mvn spring-boot:run
   ```

   o el comando equivalente que use tu proyecto.
4. (Opcional) Acceder a la consola H2 si la tenés habilitada, para ver las tablas y datos.

---

## 🧪 Pruebas y casos de uso

* Crear un paciente
* Crear un médico
* Solicitar un turno para un paciente con un médico
* Cancelar o reprogramar un turno
* Ver todos los turnos de un paciente
* Ver disponibilidad de turnos de un médico

---

## 👤 Autor

**Rodrigo / PRodri57**
Proyecto de final en Java para turnera médica.
