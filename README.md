# PSGCrc - Proyecto de Gestión Comunitaria (Community Edition v2.6.0)

PSGCrc es un sistema de gestión comunitaria de código abierto diseñado para ayudar a comunidades que aún operan con registros manuales a digitalizar su administración, permitiendo autogestión, trazabilidad y control sin necesidad de infraestructura compleja.

## Propósito
- Modernizar comunidades sin acceso a tecnología de gestión avanzada.
- Facilitar la autogestión de gastos comunes y registros de visitas.
- Reducir la dependencia de procesos manuales y el error humano.

## 🚀 Funcionalidades Principales
- **Seguridad (RBAC)**: Roles de Admin, Residente, Propietario y Conserje con permisos estrictos.
- **Motor Financiero**: Cálculo automático de gastos comunes y fondos especiales.
- **Auditoría Activa**: Registro inmutable de acciones críticas para transparencia comunitaria.
- **Digitalización de Conserjería**: Libros de novedades, registro de visitas y paquetería.
- **Arquitectura Canónica**: Sistema escalable basado en estándares SGC.

## 🛠️ Instalación Rápida
1. **Backend**:
   ```bash
   cd backend
   npm install
   cp .env.example .env # Configura tus secretos aquí
   npx prisma generate
   npx prisma db push
   npx prisma db seed
   npm run dev
   ```
2. **Frontend**:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

## 🔐 Credenciales de Prueba (Default Seed)
- **Admin**: `gdcuentas@sgc.cl` / `admin123`
- **Residente**: `residente@sgc.cl` / `sgc123`
- **Propietario**: `propietario@sgc.cl` / `sgc123`
- **Conserje**: `conserje@sgc.cl` / `sgc123`

## 📄 Licencia y Modelo de Adopción
Este proyecto se distribuye bajo la licencia **GNU Affero General Public License v3 (AGPL-3.0)**. 

### Modelo de Uso:
- **Software**: Libre para uso comunitario bajo términos AGPL. Cualquier modificación redistribuida debe compartirse bajo la misma licencia.
- **Servicios Comerciales**:
  - **Hosting y Despliegue (VPS)**: Ofrecemos instalación asistida por una tarifa.
  - **Soporte Técnico**: Soporte prioritario y mantenimiento como servicio pagado.
  - **Personalización Especializada**: Desarrollo de módulos a medida.

Para consultas comerciales o soporte profesional, contactar con el equipo de Proyecto Clafis.

## 🤖 AI Optimized
Este proyecto está diseñado para ser mantenido y escalado mediante asistentes de IA (Antigravity/ChatGPT), siguiendo el estándar documental en `/docs/architecture`.
