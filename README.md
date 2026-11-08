# Zalman R1 | Bandeja HDD 3.5"

**Soporte para discos duros de 3,5 pulgadas diseñado mediante CAD para la torre Zalman R1.**

![3D Printing](https://img.shields.io/badge/3D_Printing-STL-2563EB?style=flat-square)
![CAD](https://img.shields.io/badge/CAD-SolidWorks-64748B?style=flat-square)
![Hardware](https://img.shields.io/badge/Hardware-Zalman_R1-0F172A?style=flat-square)
![Status](https://img.shields.io/badge/Status-Prototype-F59E0B?style=flat-square)

---

## Descripción

Este repositorio contiene el diseño de una bandeja para alojar discos duros mecánicos de **3,5 pulgadas (HDD)** en la caja de ordenador **Zalman R1**.

El proyecto nace de la necesidad de adaptar y ampliar las posibilidades de montaje y organización del almacenamiento interno mediante una pieza diseñada específicamente para esta caja.

El modelo se distribuye en formato STL, compatible con programas de laminado para impresión 3D.

**Diseño y desarrollo:** Miguel Rodríguez Saiz  
**Proyecto:** Ardu Solutions  
**Categoría:** Hardware / Diseño CAD / Impresión 3D

## Características

- Diseño orientado a la caja Zalman R1.
- Alojamiento para discos duros de formato 3,5".
- Modelo tridimensional preparado para su importación en software de impresión 3D.
- Archivo STL disponible para descarga directa.
- Desarrollo CAD realizado con SolidWorks.
- Proyecto abierto a revisiones y mejoras futuras.

> **Nota:** La compatibilidad física, las tolerancias y los puntos de fijación deben comprobarse antes de utilizar la pieza con hardware definitivo.

## Archivos del proyecto

```text
zalman-r1-bandeja-hdd-3.5/
│
├── models/
│   └── DISCO35ZALMANv2.STL
│
└── README.md
```

| Archivo | Descripción | Disponibilidad |
|---|---|---|
| DISCO35ZALMANv2.STL | Modelo tridimensional para impresión 3D | Público |
| Archivo SolidWorks (.SLDPRT) | Modelo CAD original | No publicado |

### Descargar modelo 3D

**[Descargar archivo STL](https://github.com/ardu01/zalman-r1-bandeja-hdd-3.5/raw/main/models/DISCO35ZALMANv2.STL)**

El archivo también puede consultarse directamente en el [repositorio de GitHub](https://github.com/ardu01/zalman-r1-bandeja-hdd-3.5).

## Fabricación mediante impresión 3D

El modelo STL puede importarse en un programa de laminado compatible para preparar su fabricación.

### Procedimiento recomendado

1. Descargar el archivo STL del repositorio.
2. Importarlo en un programa de laminado 3D.
3. Revisar las dimensiones y la escala del modelo.
4. Seleccionar el material y configurar los parámetros de impresión.
5. Comprobar la orientación de la pieza y la necesidad de soportes.
6. Generar el archivo de impresión para la impresora correspondiente.
7. Verificar el ajuste de la pieza antes de instalar el disco duro.

### Consideraciones técnicas

Para su utilización en el interior de un ordenador, deben tenerse en cuenta:

- La temperatura de funcionamiento del equipo.
- La resistencia mecánica del material utilizado.
- Las vibraciones producidas por los discos duros mecánicos.
- La correcta fijación de la bandeja y del dispositivo.
- La separación respecto a ventiladores, cables y otros componentes.

**Importante:** No se han publicado perfiles de impresión ni resultados de ensayos mecánicos. Los parámetros de fabricación deberán ajustarse al material, a la impresora y a las condiciones de uso.

## Desarrollo CAD

El diseño se ha desarrollado utilizando **SolidWorks**, como parte de un proceso de diseño de componentes personalizados para hardware informático.

El archivo original `.SLDPRT` no está disponible públicamente en esta versión del repositorio.

El archivo STL permite visualizar la geometría y preparar su fabricación, aunque no conserva el historial paramétrico de edición de SolidWorks.

## Integridad del archivo

Se proporciona la información de integridad del modelo publicado para facilitar su verificación.

**Archivo:** `DISCO35ZALMANv2.STL`  
**Tamaño:** 8.884 bytes

**SHA-256:**

```text
be05e27b857cb8537dbc7b5ebf11fb1800a7b5c30724d213b802bc22b22a1842
```

En Windows, puede verificarse mediante PowerShell:

```powershell
Get-FileHash .\DISCO35ZALMANv2.STL -Algorithm SHA256
```

En Linux:

```bash
sha256sum DISCO35ZALMANv2.STL
```

## Evolución del proyecto

Posibles líneas de desarrollo:

- [x] Diseño del modelo CAD inicial.
- [x] Exportación del modelo a STL.
- [x] Publicación del archivo en GitHub.
- [ ] Incorporación de imágenes y renders del modelo.
- [ ] Documentación de tolerancias y dimensiones.
- [ ] Publicación de fotografías de montaje.
- [ ] Validación documentada de impresión e instalación.
- [ ] Publicación de revisiones adicionales, si fueran necesarias.

Las tareas pendientes representan posibles mejoras y no compromisos de desarrollo.

## Autor

**Miguel Rodríguez Saiz**

Diseño, modelado CAD y desarrollo del proyecto.

**Ardu Solutions**  
Desarrollo de software, hardware y soluciones tecnológicas.

- **Web:** https://ardusolutions.pages.dev/
- **GitHub:** https://github.com/ardu01
- **Repositorio:** https://github.com/ardu01/zalman-r1-bandeja-hdd-3.5

## Licencia

Este repositorio no incluye actualmente un archivo de licencia.

La publicación del modelo permite su consulta y descarga, pero no implica automáticamente la concesión de permisos para su modificación, redistribución o explotación comercial.

Para cualquier uso que requiera autorización, contactar con el titular del proyecto.

---

**© 2026 Miguel Rodríguez Saiz · Ardu Solutions**

*Diseño e ingeniería aplicada a soluciones reales.*
