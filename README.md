# Wang Restoration Boundary Demo v0.1 Report

G2 remains pending and is not used.

## Policy chain

```text
P-layer: placement policy
B0-layer: boundary-signature policy
```

## P-layer result

```text
ANY_EDGE = ANY_OFFSET
```

Measured:

```text
target≤5 max(ANY_OFFSET − ANY_EDGE): 0.000000
target-6 G3/G4 max(ANY_OFFSET − ANY_EDGE): 0.000000
```

## B0 result

Boundary-signature policy explains the tested P-layer resonance.

Measured:

```text
target≤5 mean boundary-signature purity for ANY_EDGE: 1.000
target-6 G3/G4 mean boundary-signature purity for ANY_EDGE: 1.000
```

## Escalation condition

Do not advance to B1 unless B0 becomes soft.

Advance to B1 annulus-growth policy only if:

```text
ANY_EDGE and ANY_OFFSET diverge on an admissible pair
boundary-signature purity drops below 0.90
seeds with identical boundary signatures split under restoration
```
