##Recycler View

Con la versión que será presentada por Google de android L se ha presentado el nuevo widget llamado RecyclerView.

Este nuevo Widget entra en juego cuando el propósito es mostrar gran número de Views repetidamente, listas, grids, etc…, tantas que no entran en la pantalla.
RecyclerView implementa un sistema para llevar a cabo esta tarea, de forma sencilla y eficiente.

####La API de RecyclerView

A diferencia del ListView, GridView, etc… el RecyclerView se dedica únicamente a lo que su nombre indica, reciclar, reutilizar recursos y evitar el uso reiterado del costoso findViewById, no se preocupa del aspecto visual, para ello está el LayoutManager, 

Una clase una tarea, esa es la filosofía que sigue la API del RecyclerView, un paquete de clases  internas cada una con una responsabilidad:

* Adapter
* ViewHolder
* LayoutManager
* ItemDecoration
* ItemAnimator
