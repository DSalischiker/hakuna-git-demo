# hakuna-git-demo

Repo de práctica para la clase **Git para diseñadorxs** de Studio Hakuna. Acá se puede romper todo: para eso está.

## Qué hay

- `index.html`: una página con un título y un botón.
- `styles.css`: los estilos. El botón `.btn-primary` es el protagonista del ejercicio de conflictos.

## Para practicar el flujo

1. Cloná el repo (en VS Code: **Clone Git Repository** y pegá la URL).
2. Creá tu branch desde `main`: `feature/tu-nombre`.
3. Cambiá algo en `styles.css` (un color, un padding).
4. Revisá el diff, hacé commit con un mensaje claro y publicá la branch.
5. Abrí un Pull Request en GitHub.

## Ejercicio: el conflicto en vivo

1. Dos personas parten de `main` actualizado.
2. Las dos cambian el `background` de `.btn-primary` a colores distintos y commitean.
3. La primera sube su cambio a `main`.
4. La segunda hace pull: aparece el conflicto.
5. Lo resolvemos entre todos con el Merge Editor de VS Code.

¿Te arrepentiste en el medio? `git merge --abort` deja todo como estaba.
