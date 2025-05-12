# Despliegue de Sitio Web con Alta Disponibilidad en AWS usando CloudFormation

Este proyecto demuestra el despliegue de una arquitectura de alta disponibilidad utilizando **AWS CloudFormation**, la cual incluye:

- Un balanceador de carga (Elastic Load Balancer).
- Dos instancias EC2 distribuidas en distintas zonas de disponibilidad.
- NGINX sirviendo un sitio web desde ambas instancias.
- Visualización del diseño en **CloudFormation Designer**.

---

## Capturas de pantalla

### 📌 1. Pila en estado `CREATE_COMPLETE`
*Captura 1:*  
![Imagen de WhatsApp 2025-05-10 a las 16 51 22_aa7fb9a0](https://github.com/user-attachments/assets/317913ec-738a-4207-a658-e9d3b36049dc)


---

### 📌 2. Dos instancias EC2 activas
*Captura 2:*  
![Imagen de WhatsApp 2025-05-10 a las 16 51 22_83d095d2](https://github.com/user-attachments/assets/471cd72c-8578-462c-8b38-e0d4c164e5b9)


---

### 📌 3. Acceso exitoso al sitio web mediante el Load Balancer
🔗 **Enlace de acceso al sitio web:**  
http://infraa-loadb-ihxkl0dz4inm-2104684887.us-east-1.elb.amazonaws.com/

*Captura 3.1:* Sitio activo con ambas instancias  
![Imagen de WhatsApp 2025-05-10 a las 17 46 38_5fba1771](https://github.com/user-attachments/assets/310d7215-77dc-4850-a56a-6626bf33da88)


*Captura 3.2:* Una instancia EC2 detenida, pero el sitio sigue funcionando  
![Imagen de WhatsApp 2025-05-10 a las 17 46 39_4d4067aa](https://github.com/user-attachments/assets/4cbaf7f7-0be3-4266-90e6-e65b5c27cfe4)


---

### 📌 4. Visualización en CloudFormation Designer
*Captura 4:*  
![Imagen de WhatsApp 2025-05-10 a las 16 54 43_f1970328](https://github.com/user-attachments/assets/9fd993a7-c14b-4df6-9882-f7504fc746f1)


---

## Comentarios del equipo

Cada integrante del grupo debe dejar un breve comentario sobre su experiencia o aprendizajes:

- **Marvin Rodriguez:**  
  _"Aprendí a utilizar CloudFormation de forma completa, ya que antes no conocía esta herramienta. Aunque ya sabía cómo funcionaban las instancias EC2 y el Load Balancer, descubrí que su creación se puede automatizar totalmente. Además, el diagrama visual que genera es muy útil para documentar o replicar la arquitectura en otras cuentas."_  

 



