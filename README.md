# Mora · Órdenes de trabajo · Frontend

Demo web con la identidad de Cartonajes Mora, carga de hasta 50 archivos por lote, campos configurables, listas de operarios, revisión y exportación conjunta CSV/JSON. Incluye la corrección de unidades buenas y su vista móvil.

Web publicada: https://mora-ordenes-demo.vercel.app/

API: https://github.com/Silviu2326/mora-ordenes-backend

## Vercel

Importar este repositorio. El framework es Other y el directorio público es public, definidos en vercel.json. Configurar ORIGIN_SECRET en las variables del servidor de Vercel, con el mismo valor que Railway. El proxy añade ese secreto a las solicitudes /api; no llega al navegador. Si se usa otra API, actualizar el destino HTTPS en vercel.json y FRONTEND_ORIGIN en Railway.

Comprobación del código: npm run check. No hay dependencias npm.

La configuración de campos se conserva por navegador. Los documentos y resultados permanecen en memoria durante la sesión. El ejemplo incluido es ficticio; no contiene órdenes ni fotografías reales. La publicación del repositorio no vincula automáticamente el servicio de Vercel a GitHub; el despliegue actual está gestionado mediante CLI.
