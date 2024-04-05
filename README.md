import numpy as np
import matplotlib.pyplot as plt

# Generate data for a power law distribution
x = np.linspace(-10, 10, 1000)
y = x**(-2)

# Plot the graph
plt.figure(figsize=(8, 6))
plt.plot(x, y, color='blue')
plt.title('Power Law Distribution')
plt.xlabel('X')
plt.ylabel('Y')
plt.grid(True)
plt.show()


