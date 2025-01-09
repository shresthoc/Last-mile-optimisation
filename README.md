<p align="center">
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/FedExpedite.png?raw=true" alt="FedExpedite" />
</p>

#### a python based route optimiser and emission calculator for FedEx

installation guide
-------
1. ensure that python, pip and git are installed

        sudo apt update && sudo apt-get install python3
        sudo apt-get install python3-pip
        sudo apt install git
4. clone the github repo & cd into it

        git clone https://github.com/1rvinn/FedExpedit.git && cd FedExpedit
5. install the required libraries

        pip install -r requirements.txt
7. get your api keys from [tomtom](https://developer.tomtom.com/ "tomtom") & [here](https://platform.here.com/ "here"). then update them in app.py as shown below

   ![](https://github.com/1rvinn/FedExpedite/blob/main/images/Screenshot.png?raw=true)
8. run the app

        streamlit run app.py
pipeline
-------
![](https://github.com/1rvinn/FedExpedite/blob/main/images/pipeline.png?raw=true![image])

features
-------
![](https://github.com/1rvinn/FedExpedite/blob/main/images/Screenshot%202025-01-09%20at%2019.05.28.png?raw=true)

> ### 1. route optimiser

a. flexibility to choose
+ route type
+ vehicle details
	+ vehicle type
	+ engine size
	+ fuel type
![]()
b. multi-input support
+ coordinate based
+ search based
![]()
c. user-friendly input
+fixed starting pt
+ multiple stop support
+ choice to add a fixed ending pt
![]()
d. route plan & stats
+ optimal sequence
+ total travel time
+ estimated emissions
e. gmaps integration
f.  map visualisation
![]()
> ### 2. emission calculator

a. comprehensive input factors
html
b. reliable data source
+ uses data from [India GHG Program’s report on India-Specific Road Transport Emission Factors](uses data from India GHG Program’s report on India-Specific Road Transport Emission Factors "India-Specific Road Transport Emission Factors")
