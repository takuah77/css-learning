cascading rules:

1. position
    - A) so literal order. 
    - higher up in the structure 
2. specificity
    - ID ( # )
    - Atribute (like draggable) 
    - Class ( . )
    - Element (like <h1>)
3. type
    - inline css (within an element, attribute, etc)
    - internal css (<style> )
    - external CSS (stylesheet)
4. importance
    - flag to mark as top priority (!important)

    in general, last out is the style applied. (top to the bottom; bottom wins)

    ![Alt text](image.png)