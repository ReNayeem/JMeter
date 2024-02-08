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



<h3>Report generating</h3>

<h4>open cmd in jmeter file location</h4>
<h4>run "jmeter -n -t .\file-name.jmx -l .\file-name.jtl -e -o REST_API_REPORT" (file name must not have any spaces)</h4>


<h4>END</h4>
