# python-Matplotlib
import matplotlib.pyplot as plt

# Data for plotting
x = [1, 2, 3, 4, 5]
y = [2, 3, 5, 7, 11]

# Creating the plot
plt.plot(x, y, marker='o')

# Adding titles and labels
plt.title('Simple Plot')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')

# Displaying the plot
plt.show()
