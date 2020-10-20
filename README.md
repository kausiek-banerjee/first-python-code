# first-python-code
import matplotlib.pyplot as plt
input_list = list(range(1,11))
square = [value**2 for value in range(1,11)]

fig, ax = plt.subplots()
ax.plot(input_list, square)
plt.show()
