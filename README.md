# Mother-Incubator

##DIY starter culture incubator##

Incubators are commonly used for artificial growth of microbiological cultures while maintaining the optimal temperature and other conditions such as the humidity and oxygen content of the atmosphere inside.  


A simple prototype of DIY incubator to preserve and cultivate the starters. The incubator prototype uses low-cost materials and consists of a Styrofoam box, a heat lamp, a heat sensor, and Arduino. The idea is that the heat sensor can detect the temperature in the Styrofoam box and either switch on or off the heat lamp, such that the temperature will stay within a set range of degrees. We also built a relay module to ensure that the heat lamp can be controlled using the sensor and Arduino 


![prototype](https://cloud.githubusercontent.com/assets/14889513/10266243/5a77cc96-6a88-11e5-98fd-77dada069674.jpg)


**Fails:**
* pH sensor to test for the pH values of the ferments - did not work well due to the complexity of the hardware coding
* motion sensors for easy remote-controlled ferment stirring - suggested by TeZ, but then he left and we lost

**Next:**
Replace Arduino with Photon to allow better connectivity (can have a pc from Hackerspace?)

Current version: Mother 0.1 (more or less dysfunctional prototype) -> hope to upgrade to functional Mother 1.1 soon...
