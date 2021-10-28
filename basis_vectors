import numpy as np
import matplotlib.pyplot as plt

# Vector origin location
X = [0,0]
Y = [0,0]

# Plot background
plt.style.use("seaborn-dark")
for param in ['figure.facecolor', 'axes.facecolor', 'savefig.facecolor']:
    plt.rcParams[param] = '#212946'  # bluish dark grey
for param in ['text.color', 'axes.labelcolor', 'xtick.color', 'ytick.color']:
    plt.rcParams[param] = '0.9'  # very light grey
plt.grid(color='#2A3459')  # bluish dark grey, but slightly lighter than background

# Add text coordinates in the plot
plt.text(2, 5, r'$\binom{2}{5}$', fontsize = 16,color='w')
plt.text(2, -1, r'$\binom{2}{-1}$', fontsize = 16,color='w')

# Directional vectors
U = [2,2] 
V = [5,-1]

# Plot vectors neon style
plt.quiver(X, Y, U, V, color=('#E0E722','#08F7FE'), angles='xy', scale_units='xy', scale=1,width=0.007,headwidth=4,headlength=5)

n_lines = 10
diff_linewidth = 0.002

for n in range(1, n_lines+1):
    # Creating plot
    plt.quiver(X, Y, U, V, color=('#E0E722','#08F7FE'), angles='xy', scale_units='xy', scale=1,alpha=0.03,width=0.005+(diff_linewidth*n),headwidth=1.2,headlength=3)
 
# x-lim and y-lim
plt.xticks([-6, -5, -4, -3, -2,-1,0,1,2,3,4,5,6])
plt.yticks([-6, -5, -4, -3, -2,-1,0,1,2,3,4,5,6])

# Axis labels 
plt.xlabel("X")
plt.ylabel("Y")

# Plot title
plt.title('BASIS VECTORS')

# Show plot
plt.show()

