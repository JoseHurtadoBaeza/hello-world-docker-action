# hello-world-docker-action
Repositorio para almacenar los archivos de la creación de mi propia GitHub Action

# Docker action "Hola Mundo"

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.
Esta action imprime "Hola Mundo" o "Hola" + el nombre de la persona al log

## Inputs 

### `who-to-greet`

**Requerido** El nombre de la persona a quien saludar. Por defecto `"Mundo"`

## Outputs

### `time`

La fecha en la que te saludé.

## Example usage

```
uses: tekno1796/hello-world-docker-action@v1
with:
  who-to-greet: 'Pelades'
```
