first config

# ============================================================
# EXPERIMENT CONFIGURATION - Change parameters here!
# ============================================================

# Global parameters
MAX_ITERATIONS = 500
TOLERANCE = 1e-6

# Optimizer-specific parameters
OPTIMIZER_PARAMS = {
    # Gradient-based methods
    'Gradient Descent': {'learning_rate': 0.1},
    'Momentum': {'learning_rate': 0.1, 'beta': 0.9},
    'RMSProp': {'learning_rate': 0.1, 'beta': 0.9, 'epsilon': 1e-8},
    'Adam': {'learning_rate': 0.1, 'beta1': 0.9, 'beta2': 0.999, 'epsilon': 1e-8},

    # Gradient-free methods
    'Coordinate Search': {'step_size': 0.5, 'alpha': 0.9},
    'Hooke & Jeeves': {'step_size': 0.5, 'alpha': 0.5},
    'Nelder-Mead': {}  # Uses default scipy settings
}

# Define all optimizers
optimizers = {
    'Gradient Descent': gradient_descent,
    'Momentum': momentum_search,
    'RMSProp': rmsprop,
    'Adam': adam,
    'Coordinate Search': coordinate_search,
    'Hooke & Jeeves': hooke_jeeves,
    'Nelder-Mead': nelder_mead
}

# Define all test functions
functions = ['Function1', 'Function2', 'Function3', 'Function4', 'Function5']

# Starting points to test (for sensitivity analysis - Exercise 2.2 question 4)
starting_points = [
    [0.0, 0.0],    # Origin
    [2.0, 2.0],    # Positive quadrant
    [-2.0, -2.0],  # Negative quadrant
    [3.0, -3.0],   # Mixed
]

print("=" * 70)
print("EXPERIMENT CONFIGURATION")
print("=" * 70)
print(f"Optimizers: {len(optimizers)}")
print(f"Functions: {len(functions)}")
print(f"Starting points: {len(starting_points)}")
print(f"Max iterations: {MAX_ITERATIONS}")
print(f"Tolerance: {TOLERANCE}")
print(f"\nTotal experiments: {len(optimizers)} × {len(functions)} × {len(starting_points)} = {len(optimizers) * len(functions) * len(starting_points)}")
print("=" * 70)

---

second config:

# ============================================================
# EXPERIMENT CONFIGURATION - Change parameters here!
# ============================================================

# Global parameters
MAX_ITERATIONS = 500
TOLERANCE = 1e-6

# Optimizer-specific parameters
OPTIMIZER_PARAMS = {
    # Gradient-based methods
    'Gradient Descent': {'learning_rate': 0.01},
    'Momentum': {'learning_rate': 0.05, 'beta': 0.95},
    'RMSProp': {'learning_rate': 0.05, 'beta': 0.95, 'epsilon': 1e-8},
    'Adam': {'learning_rate': 0.02, 'beta1': 0.9, 'beta2': 0.999, 'epsilon': 1e-8},

    # Gradient-free methods
    'Coordinate Search': {'step_size': 0.2, 'alpha': 0.85},
    'Hooke & Jeeves': {'step_size': 0.3, 'alpha': 0.6},
    'Nelder-Mead': {}  # Uses default scipy settings
}

# Define all optimizers
optimizers = {
    'Gradient Descent': gradient_descent,
    'Momentum': momentum_search,
    'RMSProp': rmsprop,
    'Adam': adam,
    'Coordinate Search': coordinate_search,
    'Hooke & Jeeves': hooke_jeeves,
    'Nelder-Mead': nelder_mead
}

# Define all test functions
functions = ['Function1', 'Function2', 'Function3', 'Function4', 'Function5']

# Starting points to test (for sensitivity analysis - Exercise 2.2 question 4)
starting_points = [
    [0.0, 0.0],    # Origin
    [2.0, 2.0],    # Positive quadrant
    [-2.0, -2.0],  # Negative quadrant
    [3.0, -3.0],   # Mixed
]

print("=" * 70)
print("EXPERIMENT CONFIGURATION")
print("=" * 70)
print(f"Optimizers: {len(optimizers)}")
print(f"Functions: {len(functions)}")
print(f"Starting points: {len(starting_points)}")
print(f"Max iterations: {MAX_ITERATIONS}")
print(f"Tolerance: {TOLERANCE}")
print(f"\nTotal experiments: {len(optimizers)} × {len(functions)} × {len(starting_points)} = {len(optimizers) * len(functions) * len(starting_points)}")
print("=" * 70)
