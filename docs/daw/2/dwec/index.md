# DAW 2º — DWEC

??? tip "Objetivos (clic para abrir)"
    - Entender los fundamentos de **DAW 2º — DWEC**.
    - Practicar con ejercicios guiados.
    - Consultar recursos y tareas.

=== "Explicación"
    Contenido introductorio del módulo **DAW 2º — DWEC**. Sustituye este texto por tu temario.

=== "Ejemplo ejecutable (Python)"
    ```python
    # thebe-enable
    # thebe-init
    # Ejemplo: suma y lista de cuadrados
    numeros = [1, 2, 3, 4, 5]
    suma = sum(numeros)
    cuadrados = [n*n for n in numeros]
    print("Suma:", suma)
    cuadrados
    ```

=== "Ejercicios"
    1. Crea una función `media(lista)` que devuelva la media aritmética.
    2. Pide un número `n` y muestra los `n` primeros cuadrados.

---

<details>
  <summary><strong>Solución orientativa (haz clic)</strong></summary>

```python
# thebe-enable
# thebe-init
def media(vals):
    return sum(vals)/len(vals) if vals else 0.0

nums = [2, 4, 6, 8]
print("Media:", media(nums))
```
</details>

---

### Recursos
- Apuntes en PDF (si procede)
- Repositorio de prácticas
- Foros/Plataforma del curso
