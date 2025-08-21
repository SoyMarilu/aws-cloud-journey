# Módulo 6: Seguridad en AWS 🔐

En este módulo he trabajado los **principales servicios y prácticas de seguridad en AWS**, fundamentales para cualquier perfil de **DevSecOps** o **Platform Engineer**.

---

## 🔑 Contenidos principales

- **IAM (Identity and Access Management)**
  - Creación y gestión de usuarios, grupos y roles.
  - Políticas basadas en permisos mínimos (principle of least privilege).
  - Uso de MFA (Multi-Factor Authentication).

- **AWS Organizations**
  - Estructuración de múltiples cuentas AWS.
  - SCPs (Service Control Policies) para reforzar seguridad a nivel organizacional.

- **AWS KMS (Key Management Service)**
  - Gestión de llaves de cifrado.
  - Uso de llaves en S3 y RDS para datos en reposo.

- **AWS Secrets Manager**
  - Almacenamiento seguro de credenciales y secretos.
  - Rotación automática de contraseñas.

- **AWS Config & CloudTrail**
  - Auditoría de cambios y configuraciones.
  - Monitoreo de accesos y cumplimiento.

---

## 🛡️ Buenas prácticas aprendidas

1. **Principio de privilegio mínimo** → otorgar solo los permisos estrictamente necesarios.  
2. **Cuentas separadas** para entornos (producción, desarrollo, pruebas).  
3. **Cifrado de datos** en tránsito y en reposo por defecto.  
4. **Automatizar auditorías** con AWS Config Rules y CloudTrail.  
5. **Gestión centralizada de accesos** usando AWS Organizations.  

---

## 🧰 Aplicación práctica (mini-proyectos)

- **Proyecto 1:** Configuración de roles IAM con políticas personalizadas.  
- **Proyecto 2:** Habilitar CloudTrail + AWS Config para auditar una cuenta AWS.  
- **Proyecto 3:** Implementar cifrado con KMS en un bucket S3.  

---

## 📌 Próximos pasos

- Continuar con el **Módulo 7: Redes en AWS**.  
- Integrar las prácticas de seguridad en pequeños **pipelines CI/CD** con GitHub Actions + AWS.  
- Explorar cómo estas configuraciones se refuerzan con herramientas de **DevSecOps** como:
  - **Checkov** (infra as code scanning)  
  - **Trivy** (scanning de contenedores)  

---

✍️ *Este módulo fortalece mi base en seguridad cloud, un pilar clave para mi objetivo futuro como **Platform Engineer**.*
