# ROBOT LAB — Juego de historia de la robótica

Juego estático de 5 preguntas y ensamblaje progresivo de un robot. No requiere cuentas, base de datos ni servicios de terceros.

## Publicarlo en GitHub Pages
1. Crea un repositorio público en GitHub, por ejemplo `robot-lab`.
2. Sube el archivo `index.html` a la raíz del repositorio (puedes subir también este README).
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, rama **main**, carpeta **/(root)** y pulsa **Save**.
5. Espera a que GitHub publique el sitio. La dirección suele ser `https://TU-USUARIO.github.io/robot-lab/` (sustituye el usuario y comprueba la URL real en Pages).
6. Abre el enlace en un celular y comprueba que el juego funcione.

## Código QR
Cuando tengas la URL definitiva, puedes generar un QR con `https://www.qr-code-generator.com/` o `https://goqr.me/`. Pega la URL publicada, descarga el QR e insértalo en tu diapositiva 8. Verifica que el QR abra el juego desde otro dispositivo.

## Editar preguntas
En `index.html`, busca `const questions=[` y modifica las preguntas y opciones. El campo `correct` usa índices 0, 1, 2 para las opciones A, B, C.

## Uso académico
Preguntas basadas en la presentación sobre la evolución histórica de la robótica y la inteligencia artificial. El juego no almacena datos personales.
