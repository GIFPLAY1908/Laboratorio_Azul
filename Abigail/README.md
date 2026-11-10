# agrego valores asignados a oclusion
# 4	50%	23.6 ms	42
# 8	50%	48.1 ms	21
# 16	50%	95.6 ms	10
# 32	50%	185 ms	5
# 64	50%	367 ms	3
# 16	100%	184 ms	5
# 16	20%	37.6 ms	27
# Más rápido: 4 muestras / 50% → 23.6 ms (42 FPS).
# Más lento: 64 muestras / 50% → 367 ms (3 FPS).
# Ratio: 15.5× entre extremos.
# Coste ≈ O(vértices × muestras / densidad). El radio afecta al filtrado de meshes cercanos.