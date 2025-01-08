# Jmm2025
First Repo

This is just a first step to know Github <https://github.com/Kaphle/Jmm2025/edit/main/README.md >

def type_of_pow(lhs: float, rhs: float) -> type[complex]:
    if isinstance(lhs, int) and isinstance(rhs, int) and rhs >= 0:
        return int
    if lhs < 0 and not rhs.is_integer():
        return complex
    return float
    
