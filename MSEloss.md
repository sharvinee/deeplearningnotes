## MSEloss in PyTorch

```
# import torch
import torch.nn as nn

# Define the loss function
criterion = nn.MSELoss()

# Example target values (actual values)
target = torch.tensor([1.0, 2.0, 3.0])

# Example predicted values
predicted = torch.tensor([1.5, 2.5, 2.0])

# Calculate the MSE loss
loss = criterion(predicted, target)

print(loss)  # Output: 0.25
```
