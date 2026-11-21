# Mi Dinero — aplicación financiera instalable

## Qué incluye
- Registro diario de producción, gasolina y otros gastos de trabajo.
- Distribución automática a bolsillos: recibos, InDrive/datos, deuda, ahorro, gustos personales, pareja y reserva.
- Configuración de meta diaria, deuda, provisiones y porcentajes.
- Historial, registro de abonos/pagos y copia de seguridad JSON.
- Diseño adaptable a Android y modo instalable PWA.

## Importante
Esta primera versión guarda los datos localmente en el navegador del dispositivo. No tiene sincronización en la nube ni acceso a cuentas bancarias. Exporta copias de seguridad regularmente.

## Publicar e instalar en Android
Una PWA requiere una dirección HTTPS para instalarse. La forma más sencilla:
1. Crea una cuenta en GitHub.
2. Crea un repositorio público llamado `mi-dinero`.
3. Sube todos los archivos de esta carpeta a la raíz del repositorio.
4. En Settings → Pages, selecciona Deploy from a branch, rama `main`, carpeta `/root`, y guarda.
5. Espera a que GitHub Pages publique el sitio.
6. Abre la URL publicada en Chrome en tu Android.
7. Menú ⋮ → Instalar aplicación (o Añadir a pantalla principal).

## Datos iniciales
La app arranca con meta de $50.000, deuda pendiente de $300.000, provisión de recibos de $4.375 por jornada y provisión de InDrive/datos de $2.625 por jornada. Son valores editables.

## Ajuste importante del presupuesto
La app descuenta la gasolina real que ingreses cada jornada. Las provisiones diarias se apartan de lo que queda después de los gastos de trabajo. No registra automáticamente la jornada de $71.000 que mencionaste porque no sabemos si todas las reservas propuestas se separaron efectivamente; puedes agregarla manualmente desde Registrar jornada.
