# Feliz cumpleaños, Camila 🤍

Una página de felicitación de cumpleaños, hecha con cariño en un solo lugar.

Es un recorrido corto de seis momentos —portada, un chiste de "llegué tarde",
tres sobres que se abren, un rasca y revela, un momento "nosotros" y un cierre
con una canción— inspirado en la noche del arco de foquitos y la puerta de
talavera de **Casa N°58**.

## Cómo está hecho

- Una sola página estática: [`index.html`](index.html).
- Las fotos viven en [`assets/`](assets/).
- La canción se reproduce con la API de YouTube (barra "sonando" abajo). El ID
  está en la constante `SONG_ID` dentro de `index.html`:
  - Willie Nelson — *Always on My Mind* (audio): `9ULH8_CF0os`
  - Para cambiarla, sólo reemplaza ese ID.

## Verla

Publicada con GitHub Pages (rama `main`, carpeta raíz). Para correrla en local:

```bash
# desde la carpeta del proyecto
python -m http.server 8000
# y abre http://localhost:8000
```

Hecho para ti. 🤍
