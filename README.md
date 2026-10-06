# apoya — Página de donaciones de InfoConexiones

Página estática (GitHub Pages) con los métodos de donación voluntaria para los
proyectos de **InfoConexiones**:

| Método | Uso |
|--------|-----|
| Ko-fi | Donación internacional (pago vía PayPal desde Ko-fi) |
| USDT (TRC20) | Cripto — red TRON; incluye QR |
| Binance UID | Transferencia interna entre usuarios de Binance (0 comisión) |
| Pago Móvil (Banesco 0134) | Venezuela — transferencia local |
| PayPal (correo) | Envío directo desde una cuenta PayPal |

## Personalización por app

`https://infoconexiones.github.io/apoya/?app=tasasve` → muestra "Apoya a TasasVE".
Sin parámetro → "Apoya a InfoConexiones". Apps soportadas en `APP_NAMES` (index.html).

## Política

- La compra de **TasasVE Pro** se realiza **dentro de la app** (Google Play).
- Las donaciones son un **apoyo voluntario** y **no desbloquean funciones**.
- Esta página **nunca** se vincula desde dentro de las aplicaciones (Política de Pagos
  de Google Play); se enlaza desde la **política de privacidad** y canales externos.

## Configuración

En `index.html`:
- `PAYPAL_ME_ENABLED` / `PAYPAL_ME_URL` — activa el botón PayPal.Me (desactivado por
  defecto hasta decidir la cuenta receptora).
- `APP_NAMES` — nombres por app para el parámetro `?app=`.
