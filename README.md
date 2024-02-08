<h3>setup</h3>

<h4>right click on test plan > add > threads (Users) > thread group</h4>
<h4>right click on thread group > add > sampler > http request</h4>
<h4>right click on thread group > add > listener > view result tree</h4>
<h4>right click on thread group > add > listener > summary report</h4>
<h4>right click on thread group > add > timer > constant timer (timer for per request)</h4>
<h4>right click on thread group > add > listener > user defined variables (for saving pre-defined urls, keys etc.)</h4>
<h4>right click on thread group > add > config element > http header manager (for adding content type for ex json)</h4>
<h4>right click on http request (in screenshot it's name login) > add > post processors > json extractor (for saving the token)</h4>
<h4>right click on thread group > add > config element > random variable (for creating random value)</h4>
<h4>right click on http request (in screenshot it's name login) > add > assertions > json assertion (for matching intended result like postman test cases. important because if its not used jmeter will show test correct.)</h4>
<h4>right click on http request > add > config element > csv data set config</h4>

<h3>details</h3>
<h4>std. dev. aka standard deviation means how many seconds would be ideal</h4>
<h4>throughpur aka TPS means how many request the server handled per second</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/a4375fd2-5dda-4030-ae65-12f35fed2e77)
![image](https://github.com/ReNayeem/JMeter/assets/96969117/f712947b-b2d0-4f97-bdc9-66960855fe3a)
![image](https://github.com/ReNayeem/JMeter/assets/96969117/3fb6687f-aeca-45cb-a40d-ab3114bfb9c6)
![image](https://github.com/ReNayeem/JMeter/assets/96969117/278ba1f7-179c-44e3-b943-01d507dec09c)


<h3>stress test</h3>
<h4>it means times are the same but users are gradually increasing until an error shows up</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/994a456a-29e9-4bf5-8f42-66f93b3503aa)

<h4>in this screenshot 11.66 is "lower bottleneck".</h4>


<h3>Example load test report</h3>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/8bc856e7-e920-484f-95fa-71585e1f1c89)


<h3>HTTP header manager setup</h3>


<h3>REST_API details</h3>
<h4>Test structure</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/c8d53a75-c8e2-4c9d-99d8-72e317a18f47)

<h4>Constant timer</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/ca1fcf4d-60e4-4f99-bd53-e506a396c277)

<h4>HTTP Header Manager</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/707d4055-7b56-4d44-ad7f-6a11a6dda52c)

<h4>User Defined Variables</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/acadbd35-6874-47cc-ab99-4ad90414c94b)

<h4>Random Variable</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/ba6ba9f9-343c-46fb-9b6e-2f3dd176c991)

<h4>Login</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/5f89663c-d90e-4bd9-a8ed-0c13b459ae43)

<h4>Login > JSON Extractor</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/836fdd8a-6705-4d8d-9d3e-c70354350f4c)

<h4>Create User</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/d2c6b68e-46d3-45a5-b5d8-36872394f217)

<h4>Create User > JSON Assertion</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/5681cdfe-c2e6-40cd-b535-4b8a11cd09e6)

<h4>Create User > CSV Data Set Config</h4>

![image](https://github.com/ReNayeem/JMeter/assets/96969117/20eac8d8-07b3-49f5-9a72-3c60c707c590)


<h3>Report generating</h3>

<h4>open cmd in jmeter file location</h4>
<h4>run "jmeter -n -t .\file-name.jmx -l .\file-name.jtl -e -o REST_API_REPORT" (file name must not have any spaces)</h4>


<h4>END</h4>
