
WHATSAPP IC — INSTALACIÓN

1. CONECTAR SUPABASE

- Entra a https://supabase.com
- Abre tu proyecto WhatsApp IC.
- Entra a SQL Editor.
- Ejecuta el código SQL de instalación.
- Comprueba que aparezca Success.
- En Authentication activa Anonymous Sign-ins.

2. CONFIGURAR INDEX.HTML

Abre index.html con tu editor de archivos.

Busca estas dos líneas:

const SUPABASE_URL="https://pkjwtndemghylpwmgoax.supabase.co";
const SUPABASE_ANON_KEY="PEGA_AQUI_TU_CLAVE_PUBLICA";

En SUPABASE_URL pega la Project URL exacta que aparece en Supabase.

En SUPABASE_ANON_KEY pega tu clave pública que comienza por sb_publishable_.

No uses la clave secret ni service_role.

Guarda los cambios.

3. CARPETA DE IMÁGENES

La carpeta debe quedar organizada así:

whatsapp_ic_web/
  index.html
  README.txt
  supabase.sql
  assets/
    logo-whatsapp.png

El archivo logo-whatsapp.png debe estar dentro de la carpeta assets.

No cambies el nombre del archivo ni el de la carpeta.

4. PUBLICAR LA PÁGINA

Puedes publicar el proyecto en Netlify o Vercel.

Debes subir la carpeta completa, incluyendo assets.

No subas únicamente index.html porque el logo no aparecerá.

5. FUNCIONES

- Registro con usuario de Discord.
- Nombre de WhatsApp IC.
- Foto de perfil.
- Número IC automático de seis dígitos que comienza por 3.
- Agregar contactos por número.
- Conversaciones privadas.
- Crear grupos.
- Enviar mensajes en tiempo real.
- Publicar estados con colores.
- Estados que desaparecen después de 24 horas.

6. IMPORTANTE

El usuario de Discord es un texto y todavía no se verifica mediante Discord OAuth.

Las cuentas anónimas quedan vinculadas al navegador.

Si se borran los datos del navegador, se puede perder el acceso a la cuenta.

Nunca pongas claves secretas de Supabase dentro del HTML.

La clave pública es la que se utiliza en esta página.

