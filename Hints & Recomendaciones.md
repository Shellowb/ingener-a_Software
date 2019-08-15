# Hints y Preguntas de controles ing.

## Hints
### Materia
#### Objetivos
El hint del **objetivo de negocio:** que  es lo que quiere el cliente con el negocio
#### Requisitos
Requisito o no, y por qué: El sistema será fácil de usuario a los empleados después de un entrenamiento <br>
Ojo cuando hay dos requisitos juntos

### Proyecto
[Draw.io](https://www.draw.io/) nos puede ayudar a ver los diagramas de caso de uso
usar *usuarios predeterminados* de django

## Preguntas de controles anteriores:
### Requisitos
- ¿ Es un requisito o qué?
> Completos, claros y verificables

- El sistema le será fácil de usar para el usuario después de un entrenamiento usar
> Uno no sabe si va haber un entrenamiento (no se refiere a que alguien le enseñe a usar el sistema), le falta verificación (¿Qué es el entrenamiento inicial? ¿Qué se define como fácil de usar?)

- La base de datos tendrá 10 años de registro.
> Podría ser un problema que pueda verificar el registro por 10 años, pero se puede preparar la base de datos para que pueda guardar los datos durante 10 años de uso. (Es correcto) No hay que pensar en casos muy exter

- La demora máxima entre la transacción de una factura será de 2 horas.
> Es completo -> Que no sea ambiguo

- Varios usuarios podrán estar al mismo tiempo sin tiempos de retardos largos
> No es verificable ni claro, no se de

- Durante la noche se hará un backup de todas las cosas que se hicieron durante el día y el usuario podrá revisarlo cuando lo estime conveniente
> Error común: son como dos requisitos juntos. deberían por separado
Falla en verificable y claro

- El sistema debe soportar muchos usuarios a la vez
> No define cuantos son muchos usuarios

- Si el sistema falla durante la ejecución debe tener una perdida de información
> ¿Cuanta perdida de información debería ser?
anote eso
