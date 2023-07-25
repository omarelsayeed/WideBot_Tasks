###Results on all the test sets


![image](https://github.com/omarelsayeed/WideBot_Tasks/assets/64399795/e21b9b05-7560-4e80-9ae5-7d350daaa6df)


### Results on each class

![image](https://github.com/omarelsayeed/WideBot_Tasks/assets/64399795/3744a837-a475-48a4-bcb9-7a88eca61a4f)


## Training :

1- AdamW optimizer , 0.01 Wd
2- Simple AraBert as a base model
3- Linear Scheduler with warmup of 0.05

## Possible Improvements:

1- Train more as i only trained for 1 epochs
2- Try different pretrained models rather than arabert
3- attaching the author name to the story might help
4- Data Augmentations : masking , random cropping , sentence shuffeling
