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
<p>
	<img src="https://github.com/1rvinn/FedExpedite/blob/main/images/pipeline_final.png?raw=true!" alt="FedExpedite" width="600"/>
</p>

features
-------
<p>
	<img src="https://github.com/1rvinn/FedExpedite/blob/main/images/Screenshot%202025-01-09%20at%2019.05.28.png?raw=true" alt="FedExpedite" width="600"/>
</p>

### 1. route optimiser

#### a. flexibility to choose
+ route type
+ vehicle details
	+ vehicle type
	+ engine size
	+ fuel type
<p>
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/image-2.png?raw=true" alt="FedExpedite" width="200"/>
</p>

#### b. multi-input support
+ coordinate based
+ search based
<p>
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/image-3.png?raw=true" alt="FedExpedite" width="200"/>
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/image-4.png?raw=true" alt="FedExpedite" width="200"/>
</p>

#### c. user-friendly input
+ fixed starting pt
+ multiple stop support
+ choice to add a fixed ending pt
<p>
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/image-5.png?raw=true" alt="FedExpedite" width="200"/>
</p>

#### d. route plan & stats
+ optimal sequence - uses the held karp method in dynamic programming to solve for the optimal route
+ total travel time
+ estimated emissions 

#### e. gmaps integration

#### f.  map visualisation
<p>
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/image-11.png?raw=true" alt="FedExpedite" width="500"/>
</p>

### 2. emission calculator

#### a. comprehensive input factors
<p>
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/image-6.png?raw=true" alt="FedExpedite" width="150"/>
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/image-7.png?raw=true" alt="FedExpedite" width="150"/>
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/image-8.png?raw=true" alt="FedExpedite" width="150"/>
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/image-9.png?raw=true" alt="FedExpedite" width="150"/>
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/image-10.png?raw=true" alt="FedExpedite" width="150"/>
</p>

#### b. reliable emissions data source
+ uses data from [India GHG Program’s report on India-Specific Road Transport Emission Factors](https://shaktifoundation.in/wp-content/uploads/2017/06/WRI-2015-India-Specific-Road-Transport-Emission-Factors.pdf "India GHG Program’s report on India-Specific Road Transport Emission Factors")
