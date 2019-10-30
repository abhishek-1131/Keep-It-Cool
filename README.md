<pre>    <img src='images/NASA-Logo-Large.jpg' width=20% height=20%/>                  <img src='images/logo.png' width=20% height=20%/>                  <img src='images/1 Yf66eLjU4H3g7pIvpXlM5w.jpeg' width=20% height=20%/> </pre>

# Keep-it-cool
Presented at NASA International Spaceapps 2019 <br/>
<br/>
Refer 'Team Kugelblitz.pptx' for our full work and roadmap.

<img src='images/homepage.PNG' width=100% height=50%/>

## Climate change impact visualizer
Keep it cool is visualization tool that maps NASA's GISTEMP data on a WebGL based globe, and displays the impact of climate change on global mean temperature over the past century. This visualization work was inspired by the work done by Chrome Experiments (WebGL) and people like A. Sweeney, Yoshua Bengio and many others' work in visualizing climate change.<br/>
Red/orange spikes = higher global temperatures than average (anomalies)<br/>
Blue/purple spikes = lower global temperatures than average <br/>
### 1910s
<img src='images/19s.PNG' width=100% height=50%/> <br/>
### 2010s
<img src='images/20s.PNG' width=100% height=50%/> <br/>

## Global mean temperature predictor 
We implemented a regression model that can tell the global temperature at any time in the future, given the CO2 emissions. It provides an interactive feedback for the user to play around with and see what the effects of CO2 emissions in the future years, could mean for the global mean temperatures.

### Example
First field: Year <br/>
Second field: CO2 levels in ppm <br/>
<img src='images/350.PNG' width=100% height=50%/> <br/>
<img src='images/456.PNG' width=100% height=50%/> <br/>
<img src='images/700.PNG' width=100% height=50%/> <br/>
