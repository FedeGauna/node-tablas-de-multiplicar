# Tablas de Multiplicar

Generador de tablas de multiplicar desde la línea de comandos. Crea archivos de texto con la tabla deseada.

## Requisitos

- [Node.js](https://nodejs.org/) (v18 o superior)
- [pnpm](https://pnpm.io/)

## Instalación

```bash
pnpm install
```

## Uso

```bash
pnpm start --base=5
```

### Opciones

```
  --help     Muestra ayuda                                    [booleano]
  --version  Muestra número de versión                        [booleano]
  -b, --base     Base de la tabla de multiplicar              [número] [requerido]
  -l, --listar   Muestra la tabla en consola                  [booleano] [defecto: false]
  -h, --hasta    Límite de valores a multiplicar por la base  [número] [defecto: 10]
```

### Ejemplos

Generar la tabla del 5 y mostrarla en consola:

```bash
pnpm start --base=5 --listar
```

Generar la tabla del 7 hasta el 15:

```bash
pnpm start --base=7 --hasta=15
```

Con opciones abreviadas:

```bash
pnpm start -b 3 -l -h 12
```
