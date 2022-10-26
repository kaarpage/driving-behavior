# driving-behavior

The problem addressed consists to observe the behavior of drivers during a car trip and prevent fatal accidents. A study by the AAA Foundation for Traffic Safety reveals that 106,727 of fatal car accidents were caused by aggressive behavior by drivers. It is important to note that this aggressive behavior is also generated from the behavior of other drivers in traffic who are slower than usual.
For example, if there is a driver in front of you that is slower than you should be, a driver's natural instinct is to try to overtake them. But, with that, the chance of this "aggressive" driver being or generating a victim of an accident (with chances of being fatal) is very high.

Aggressive driving includes speeding, sudden braking and sudden left or right turns. All these events are reflected in the accelerometer (Acc) and gyroscope (Gyro) data, which are described in x, y, z vectors.
In addition to the accelerometer and gyroscope data, the time in seconds that that event happened and the classification of the driver's behavior are also obtained.
Knowing that a traffic accident only happens when the driver has an aggressive or slow behavior, the target class was divided into two classifications: normal or abnormal behavior. Then, he observed the relationship between the information from various data visualization methods in order to understand a little more about the problem at hand before performing the training of the models.
