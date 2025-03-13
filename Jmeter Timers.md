# Jmeter Timers: Constant, Gaussian Random, Uniform [Example]

## What are Timers?

By default, JMeter sends the request without pausing between each request. In that case, JMeter could overwhelm your test server by making too many requests in a short amount of times.

Let imagine that you send thousands request to a web server under test in a few seconds. This is what happens!

![alt text](TimersImages/image.png)

Timers allow JMeter to **delay** between each request which a thread makes. A timer can solve the server **overload** problem.

Also, **in real life visitors do not arrive at a website all at the same time, but at different time intervals. So Timer will help mimic the real-time behavior.**

Following are some **common** types of a timer in JMeter

## Constant Timer

Constant timer delays each user request for the **same** amount of time.

![alt text](TimersImages/image2.png)

## Gaussian Random Timer

Gaussian random timer delays each user request for a **random** amount of time.

![alt text](TimersImages/image3.png)

## Parameters
| Attribute                      | Description                                           |
|--------------------------------|-------------------------------------------------------|
| Name                           | Descriptive name for this timer that is shown in the tree |
| Deviations (milliseconds)      | A parameter of Gaussian Distribution Function         |
| Constant Delay Offset (milliseconds) | Additional value in milliseconds                    |

So the total delay is described as below figure:

![alt text](TimersImages/image4.png)

## Uniform Random Timer

Uniform random timer delays each user request for a random amount of time.

![alt text](TimersImages/image5.png)

### Parameters
| Attribute                      | Description                                           |
|--------------------------------|-------------------------------------------------------|
| Name                           | Descriptive name for this timer that is shown in the tree |
| Random Delay Maximum           | Maximum random number of milliseconds to delay.       |
| Constant Delay Offset (milliseconds) | **Additional** value in milliseconds                    |

**The total delay is the sum of the random value and the offset value.**

### BeanShell Timer
The BeanShell Timer can be used to **generate** a delay time between each user request.

### BSF Timer
The BSF Timer can be used to generate a delay between each user request using a BSF scripting language.

### JSR223 Timer
The JSR223 Timer can be used to generate a delay between each user request using a JSR223 scripting language

## How to Use Constant Timer
In this example, you will use **Constant Timer** to set **a fixed delay** between user requests to google.com.

Let start with a simple test script

1. JMeter creates one user request to http://www.google.com **100** times
2. Delay between each user request is **5000** ms
Here is the **roadmap** for this practical example:
