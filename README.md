# [NOMBRE-DEL-REPO]  <!-- elige el nombre, p. ej. feast-dirac-engine -->

Spectral eigensolver for the radial Dirac equation and for screened-Coulomb
(Yukawa / Debye) bound states and resonances. The solver uses an orthonormal
generalized-Laguerre basis with an exact-structure discretization, a
mass-shifted pencil, complex scaling for resonances, and FEAST-type contour
integration. Run-time identity checks certify every matrix assembly.

**Author:** César D. Reinoso (Escuela Superior Politécnica de Chimborazo,
Riobamba, Ecuador).

## Qué incluye

| Módulo | Rol |
|---|---|
| `dirac.py` | Motor relativista (Dirac radial): base L-spinor, escalera exacta, Dirac--Coulomb |
| `basis.py` | Motor no relativista (Laguerre ortonormal) para el problema apantallado |
| `feast.py` | Integración de contorno tipo FEAST |
| `reference_fd.py` | Referencia independiente para validación cruzada |

<!-- Copiar estos archivos desde src/ del repo de trabajo al preparar el repo. -->

## Requisitos

- Python >= 3.10
- numpy, scipy

## Uso mínimo

```python
# ejemplo breve de API, a completar con la interfaz real de dirac.py / basis.py
```

## Trabajos que lo usan

Este motor da soporte a los cálculos de reproducibilidad de los manuscritos
A (Dirac, CPC), B (resonancias, EPJ D), D (Stark--Debye, J. Phys. B) y
T (teorema, IMA JNA), todos en preparación.

## Cómo citar

Se asignará un DOI persistente (p. ej. Zenodo) al publicar.

```
[CITA / DOI pendiente]
```

## Licencia

MIT. Ver [LICENSE](LICENSE). © 2026 César D. Reinoso.
