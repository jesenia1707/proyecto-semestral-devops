# Proyecto Semestral DevOps

## Descripción

Este proyecto corresponde al desarrollo e implementación de una solución basada en prácticas DevOps, utilizando una arquitectura de microservicios desplegada sobre Amazon Web Services (AWS).

La aplicación está compuesta por un frontend desarrollado en React, dos microservicios implementados con Spring Boot y una base de datos MySQL. Todo el sistema fue contenerizado mediante Docker y desplegado utilizando Amazon Elastic Kubernetes Service (Amazon EKS).

---

## Arquitectura

La solución está compuesta por:

- Frontend React
- Microservicio Ventas (Spring Boot)
- Microservicio Despachos (Spring Boot)
- Base de datos MySQL
- Docker
- Docker Compose
- GitHub Actions
- Amazon Elastic Container Registry (ECR)
- Amazon Elastic Kubernetes Service (EKS)
- Amazon CloudWatch

---

## Tecnologías utilizadas

- React
- Spring Boot
- Java 17
- Maven
- MySQL
- Docker
- Docker Compose
- Kubernetes
- Amazon EKS
- Amazon ECR
- GitHub Actions
- AWS CLI
- CloudWatch

---

## Estructura del proyecto

```
proyecto-semestral/

├── front_despacho/
├── back-Ventas_SpringBoot/
├── back-Despachos_SpringBoot/
├── mysql/
├── k8s/
├── .github/
│   └── workflows/
│       └── devops.yml
├── docker-compose.yml
└── README.md
```

---

## Ejecución local

### Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/proyecto-semestral-devops.git
```

Ingresar al proyecto

```bash
cd proyecto-semestral-devops
```

Levantar el entorno

```bash
docker compose up -d
```

---

## Pipeline CI/CD

El proyecto incorpora un pipeline de Integración y Entrega Continua implementado mediante GitHub Actions.

El pipeline realiza automáticamente las siguientes tareas:

- Descarga del código fuente.
- Compilación de los microservicios.
- Construcción de imágenes Docker.
- Publicación de imágenes en Amazon ECR.
- Actualización del despliegue sobre Amazon EKS.

---

## Despliegue en AWS

La solución fue desplegada utilizando los siguientes servicios:

- Amazon EKS
- Amazon ECR
- Amazon CloudWatch
- Elastic Load Balancer
- IAM

---

## Funcionalidades

- Consulta de órdenes de compra.
- Gestión de despachos.
- API REST documentada mediante Swagger.
- Contenerización con Docker.
- Despliegue en Kubernetes.
- Integración continua mediante GitHub Actions.

---

## Integrantes

- Jesenia Pardo
- Bárbara Araya

Asignatura: DevOps

Duoc UC

2026