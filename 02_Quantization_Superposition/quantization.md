# Quantization: Discrete by Confinement

**Classical First:** Review a continuous system. A ball on a smooth ramp can rest at any height, meaning its potential energy can have any value within a continuous range. There are no forbidden energy values.

**Quantum Concept:** Quantization is the principle that physical properties, like energy, can only take on specific, discrete values. It's not a dial you can turn smoothly; it's a switch with fixed positions.

### The Guitar String Analogy

This isn't as strange as it first sounds. Quantization is a natural outcome of confining a wave. Think of a guitar string:

*   It can only vibrate at specific frequencies (the fundamental note and its overtones/harmonics).
*   It cannot vibrate at frequencies *in between* these harmonics. The vibration is quantized.

An electron trapped in an atom is similar. Its wave-like properties are confined by the atom's electric field. Because of this confinement, the electron can only exist in specific energy levels.

*   When an electron moves from a higher energy level to a lower one, it emits a photon of light with an energy corresponding *exactly* to the difference between the levels.
*   This is why elements emit and absorb light at specific, characteristic frequencies (their atomic spectra).

```mermaid
graph TD
    subgraph "Classical Ramp (Continuous)"
        A[Ball can have ANY energy E] -- slides to --> B[Any other energy E'];
    end

    subgraph "Quantum Atom (Discrete)"
        C(Energy Level 3) -- emits photon --> D(Energy Level 2);
        D -- emits photon --> E(Energy Level 1);
        style C fill:#f9f,stroke:#333,stroke-width:2px
        style D fill:#f9f,stroke:#333,stroke-width:2px
        style E fill:#f9f,stroke:#333,stroke-width:2px
    end

    subgraph "Forbidden Zone"
        F(No electron can exist here)
        style F fill:#ccc,stroke:#333,stroke-dasharray: 5 5
    end

    D -- x -- F -- x -- C;
```

This phenomenon—quantized energy levels—is a direct consequence of the electron's wave-like nature being confined within the atom.
