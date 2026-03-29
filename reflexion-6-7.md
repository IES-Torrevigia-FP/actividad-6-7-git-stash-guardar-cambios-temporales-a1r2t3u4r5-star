## ¿Qué es git stash y en qué se diferencia de hacer commit?

Git stash es una herramienta que permite guardar cambios temporales en el repositorio sin necesidad de hacer un commit.

La diferencia principal con un commit es que el commit guarda los cambios de forma permanente en el historial del proyecto, mientras que el stash es temporal y no forma parte del historial. El stash se usa para pausar el trabajo

---

## Situaciones reales donde usaría git stash

1. Cuando estoy trabajando en una funcionalidad pero necesito cambiar rápidamente a otra rama para arreglar un bug urgente sin mezclar cambios incompletos.

2. Antes de hacer un pull del repositorio remoto, para evitar conflictos con cambios locales que todavía no están listos para commit.

---

## Riesgos de abusar de git stash

- Puedes olvidar cambios importantes guardados en stashes.
- Si no usas mensajes descriptivos, es difícil saber qué contiene cada stash.
- Acumular muchos stashes puede generar confusión y te pierdes el orden.
- Existe el riesgo de perder trabajo si eliminas un stash por error.

En general, git stash es útil, pero debe usarse con cuidado y organización.
