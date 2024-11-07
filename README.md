# Endpoints API Documentación

A continuación se describen los principales endpoints de la API.

## Autenticación y Registro

### Iniciar sesión
- **Método**: POST
- **Endpoint**: `/login`
- **Descripción**: Inicia sesión del usuario verificando las credenciales proporcionadas. Si las credenciales son correctas, establece la sesión.

**Ejemplo de cuerpo de solicitud**:
```json
{
    "username": "usuario123",
    "password": "contraseña"
}
