# Hypothesis_Testing_Z_test
We will use Z test to check the hypothesis that a Software Upgrade by a Telecom company had impact on 5G Uptime of customers

## The TeleCom company pushed a new Software version in the entire country to improve 5G uptime.

__Scenairo 1__ : The avg 5G uptime of the state of Virginia is different/same when compared to the entire country

![image](https://github.com/SrijanDeo-DA-DS/Hypothesis_Testing_Z_test/assets/88278620/0637b1cf-40f4-4ec1-a4b0-6a5b63817b5e)

__Conclusion__ : We will be using 1 sample Z test to calculate the stats and accept/reject null hypothesis

__Scenairo 2__ : The avg 5G uptime of the state of Virginia is different/same from the avg 5G uptime of the state of New York

![image](https://github.com/SrijanDeo-DA-DS/Hypothesis_Testing_Z_test/assets/88278620/8ca566bb-91e2-43d5-9114-e25898473032)

__Conclusion__ : We will be using 2 sample unpaired (independent) Z test to calculate the stats and accept/reject null hypothesis

__Scenairo 3__ : The avg 5G uptime of the state of Virginia is different/same from the avg 5G uptime it had before the Software push

![image](https://github.com/SrijanDeo-DA-DS/Hypothesis_Testing_Z_test/assets/88278620/61f6739a-44d9-4448-b2cd-f60fec4da2f4)

__Conclusion__ : We will be using 2 sample paired (dependent) Z test to calculate the stats and accept/reject null hypothesis


Below code is a sample code that is used to calculate Z test in Python :

![image](https://github.com/SrijanDeo-DA-DS/Hypothesis_Testing_Z_test/assets/88278620/0675f31d-f842-4bd0-b044-c9ad0e7e5a2b)

The first element of the output is the Z statistics and second element is the p-value. We assume p-value threshold to be p=0.05

## Note : We could use t-test for all the above scenarios if sample size was <=30 or the population variance / standard deviation is unknown. 


