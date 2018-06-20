# MARS PROJECT

# CHASSIS
A chassis is the internal framework of an artificial object, which supports the object in its construction and use. An example of a chassis is a vehicle frame, the underpart of a motor vehicle, on which the body is mounted.
In an electronic device, the chassis consists of a frame or other internal supporting structure on which the circuit boards and other electronics are mounted.

# DIFFERENTIAL CHASSIS
A differential wheeled robot is a mobile robot whose movement is based on two separately driven wheels placed on either side of the robot body. It can thus change its direction by varying the relative rate of rotation of its wheels and hence does not require an additional steering motion.
If both the wheels are driven in the same direction and speed, the robot will go in a straight line. If both wheels are turned with equal speed in opposite directions, the robot will rotate about the central point of the axis. Otherwise, depending on the speed of rotation and its direction, the center of rotation may fall anywhere on the line defined by the two contact points of the tires. While the robot is traveling in a straight line, the center of rotation is an infinite distance from the robot. Since the direction of the robot is dependent on the rate and direction of rotation of the two driven wheels, these quantities should be sensed and controlled precisely.
A differentially steered robot is similar to the differential gears used in automobiles in that both the wheels can have different rates of rotations, but unlike the differential gearing system, a differentially steered system will have both the wheels powered. Differential wheeled robots are used extensively in robotics, since their motion is easy to program and can be well controlled. Virtually all consumer robots on the market today use differential steering primarily for its low cost and simplicity.
![differential](https://ai2-s2-public.s3.amazonaws.com/figures/2017-08-08/176dd7b3289267d8c693fb16f0d6fea480b5fad5/2-Figure2-1.png)

# HARDWARE
assembly of the chassis for the bot using:

1.Caster wheel

![caster wheel](http://daduino.co.kr/web/product/big/201503/793_shop1_138835.jpg)

2.encoder(x2)

![encoder](https://uge-one.com/image/cache/catalog/catalog/0%20UGE%20ROTARY%20ENCODER%20400PPR-500x375.jpg)

3.wheeel(x2)

4.DC geared motor(12V)(x2)

![motor](https://robu.in/wp-content/uploads/2015/10/SPG30E-20K2-800x800.jpg)

5.spur gears(x4)

![spur gear](http://cdn.buysnip.com/2pcs-Plastic-Spur-gear-for-DIY-Projects-01.jpg)

6.Arduino Uno(x2)

![arduino](https://cf1.s3.souqcdn.com/item/2013/10/11/61/86/78/0/item_XL_6186780_3246529.jpg)

7.3D printed parts

# WORK
The bot is made up of aluminium channels as the supporting framework on which 2 ATC Motors(12V), 2 Encoders are mounted at the back of the bot.Movement is based on two separately driven wheels placed on either side of the robot body.Each wheel is connected to the motor via shaft and coupling on which a spur gear is mounted. Another spur gear is mounted on the shaft connnected to encoder. Encoder are placed such that both the shafts are kept parallel so that the gears are mated.
The motion of the bot is then programmed and controlled using arduino which is mounted on the chassis connected to the encoder. thus encoder gets the input accordingly and rotates the gear ar per the requirement which then rotates the gear connected to motor and the wheel. Therefore each wheel can have a different relative rate of rotation which is responsible for the change in direction of the bot.
Another wheel called castor wheel is mounted at the front of the bot. This wheel is kept free and can move in any direction and act as an supporting wheel. 

## WORK LEFT:

-Mounting of 3D printed gears on both sides of bot.

-Mounting of Arduino and electronics work.

# TEAM MEMBERS:

-SOURABH SONKER

-RAHUL GUPTA
