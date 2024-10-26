## Task 1.5

For simple config

```
    PTS = 50
    DATASET = minitorch.datasets["Simple"](PTS)
    HIDDEN = 10
    RATE = 0.5
```

we have such training data:

![Training loss](images/train_loss1.png)
![Train plot](images/train_plot1.png)

By the way, `HIDDEN=2` model does not train.

For xor dataset I chose `hidden_size=16` and 1k epochs. Results:


![Training loss](/Users/timsenin/github-classroom/minitorch/minitorch-module-1-Timofon/project/images/train_loss2.png)
![Train plot](/Users/timsenin/github-classroom/minitorch/minitorch-module-1-Timofon/project/images/train_plot2.png)
