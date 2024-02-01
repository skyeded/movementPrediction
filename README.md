## Predict the the future movement of human

Using GAN or Generative Adversarial Network?

### Tesla's Auto Pilot prediction uses movement prediction (?)

**AI Algorithms used**: cNN, rNN and reinforced learning.

_The system utilizes a combination of cameras, radar, and ultrasonic sensors to analyze the car's surroundings and respond to new situations on the road. Machine learning algorithms are used to recognize patterns in the data gathered by these sensors, which are then used to make decisions about how the car should respond to changing conditions._

![Tesla prediction](https://media.cnn.com/api/v1/images/stellar/prod/190419145230-01-tesla-autopilot.jpg?q=w_1110,c_fill/f_webp)

***If the car detects a pedestrian crossing the road, the algorithms can analyze the movement patterns of the pedestrian and predict their future trajectory. This allows the car to adjust its speed and path to avoid a collision. As more data is collected, the system becomes better at recognizing and responding to different types of situations (Reinforcement learning), ultimately improving the overall safety and performance of the car.***

## Basic idea

Map the skeletal points received from the prediction of AI (~~from the trained model), then map the texture onto the output using planar-based mapping (?) from the 3 different angles of the cameras.

### Possible Models

**GAN**

Unsupervised learning - The data needed for GAN is multiple movement of patient before surgery.

**LSTM RNN**

Supervised learning - The data needed for RNN is the movement of the patient before the surgery and the movement after undergoing surgery. The data will be trained in the model with the input (movement before surgery) and output the result (movement after the surgery).

***This could be effective!*** because RNN is used for **Timeseries Analysis**.

Time Series Analysis is 
a specific way of analyzing a sequence of data points collected over an interval of time.

![image](https://github.com/skyeded/movementPrediction/assets/113011883/beac4213-3ba7-4f51-9158-a1698f02c41c)

![image](https://github.com/skyeded/movementPrediction/assets/113011883/99c00847-90ee-49c7-a413-4b2caa988b77)

Mix supervised learning with unsupervised learning.
