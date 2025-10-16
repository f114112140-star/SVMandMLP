SVM 的訓練過程數學推導  
MLP 的訓練過程數學推導  

程式中如何實現 w* = w + Δw

```python
import numpy as np

# 假設我們有 w 與損失函數梯度 grad
w = np.array([0.5, -0.2, 0.1])
grad = np.array([0.05, -0.1, 0.02])
eta = 0.1  # 學習率

# 更新
delta_w = -eta * grad
w_new = w + delta_w

print("Δw =", delta_w)
print("w* =", w_new)

