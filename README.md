# Explorador de carreras UNCUYO

Micrositio estático preparado para GitHub Pages. No necesita instalar programas ni compilar código.

La versión incluida reproduce las 143 entradas de carreras, orientaciones y ciclos consignadas en la Guía de carreras UNCUYO suministrada. También incorpora los logos institucionales dentro de la carpeta `assets`, utiliza el fondo general `#f0eeff`, textos en `#2b2b2d`, botones azules `#475ae2` y el Camino institucional como fondo translúcido.

## Publicarlo en GitHub Pages

1. Crear un repositorio nuevo en GitHub, por ejemplo `explorador-carreras-uncuyo`.
2. Subir `index.html` y `.nojekyll` a la raíz del repositorio.
3. Entrar en **Settings → Pages**.
4. En **Build and deployment**, elegir **Deploy from a branch**.
5. Seleccionar la rama **main**, carpeta **/(root)** y guardar.
6. GitHub mostrará la dirección pública luego de unos minutos.

## Actualizar carreras

Abrir `index.html` y buscar la línea que comienza con `const rows=`. Cada carrera ocupa una línea con este formato:

`Nombre|Duración|Código de unidad académica|Familia|Tipo`

Los enlaces institucionales están en el bloque `const units`. Los enlaces directos de carreras particulares se pueden agregar en el bloque `const direct`.

## Importante

Antes de publicarlo como guía oficial, verificar nombres, duraciones, modalidades y enlaces con cada unidad académica.
