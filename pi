import numpy as np

x = np.random.uniform(-1, 1, 100000)
y = np.random.uniform(-1, 1, 100000)
inner = []
for i in range(len(x)):
  if (x[i] ** 2 + y[i] ** 2) < 1:
    inner.append(x[i])
pi = 4*len(inner)/100000
print(pi)
