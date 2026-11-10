# Frata TeklaFlow para Revit

Frata TeklaFlow es un complemento para Autodesk Revit desarrollado por Frata Ingenieros SAC. Intercambia elementos y armadura entre
**Revit** y **Tekla Structures**, en los dos sentidos.

Este repositorio contiene el instalador oficial y las versiones disponibles del complemento.

## Versión disponible

| Versión | Fecha de publicación | Revit compatible | Instalador |
| --- | --- | --- | --- |
| `3.0.0` | 09/11/2026 | Revit 2026, 2027 | [`FrataTeklaFlow-3.0.0.exe`](https://github.com/FRATA-Ingenieros/frata-tekla-flow-installer/releases/download/v3.0.0/FrataTeklaFlow-3.0.0.exe) |

## Qué hace

- **Tekla -> Revit:** crea en Revit las piezas y los refuerzos que seleccionas en Tekla.
- **Revit -> Tekla:** crea en Tekla las columnas, vigas, muros, losas y refuerzos que seleccionas en Revit.
- **Equivalencias editables** entre los dos programas (parámetros, diámetros, ganchos y clases), que se conservan al actualizar.

## Requisitos

| | |
| --- | --- |
| Autodesk Revit | 2026 o 2027 |
| Tekla Structures | Instalado y abierto con el modelo de trabajo |
| Sistema | Windows de 64 bits; permisos de administrador para instalar |

## Cómo instalar

1. Descargar el instalador: [`FrataTeklaFlow-3.0.0.exe`](https://github.com/FRATA-Ingenieros/frata-tekla-flow-installer/releases/download/v3.0.0/FrataTeklaFlow-3.0.0.exe)
2. **Cerrar Autodesk Revit** antes de iniciar la instalación (el instalador lo comprueba).
3. Ejecutar `FrataTeklaFlow-3.0.0.exe`, permitir la ejecución si Windows lo solicita y seleccionar los años de Revit donde instalarlo.
4. Abrir Revit y verificar que aparece la pestaña **Frata** con el panel **Tekla**: *Tekla To Revit* y *Revit To Tekla*.

Si ya existe una instalación anterior del complemento, el instalador la reemplaza y **conserva tus archivos de equivalencias**.

## Actualizaciones

El *Frata Update Manager* se instala con el producto, arranca con Windows y avisa cuando hay una versión nueva en este repositorio.
Para actualizar basta con cerrar Revit y aceptar el aviso.

## Desinstalar

Panel de control > *Aplicaciones* > **Frata TeklaFlow**. Tus archivos de equivalencias no se borran.

## Historial de versiones

| Versión | Fecha | Revit soportado | Notas |
| --- | --- | --- | --- |
| `3.0.0` | 09/11/2026 | 2026, 2027 | Primera versión como Frata TeklaFlow: instalador propio y librería Frata compartida con el resto de productos. |

## Más información

<https://www.frataingenieros.com/>
