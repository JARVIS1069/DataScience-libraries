# Different types of arrays in Numpy are
1. All 0's matrix
2. All 1's(identity) matrix

eg-
```
import numpy as np
np.zeros((2,2,2))
```
![Screenshot 2024-08-20 063539](https://github.com/user-attachments/assets/7ff8b077-0ad5-47f9-a199-0a87c335d7b4)

eg-
```
import numpy as np
np.ones((4,2,2))
```
![Screenshot 2024-08-20 063721](https://github.com/user-attachments/assets/ea042d77-4a5d-41f5-acbf-70cfa29c4666)

# Mixing ones and identity matrix-
```
import numpy as np
output = np.ones((5,5))
print(output)

z = np.zeros((3,3))
z[1,1] = 10
print(z)

output[1:4 ,1:4] = z
print(output)
```
![Screenshot 2024-08-20 064002](https://github.com/user-attachments/assets/75474434-cf18-4cda-9d6b-950975edc1bb)
