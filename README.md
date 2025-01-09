<p align="center">
  <img src="https://github.com/1rvinn/FedExpedite/blob/main/images/FedExpedite.png?raw=true" alt="FedExpedite" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&color=blue" alt="Python" />
</p>
"a python based route optimiser and emission calculator for FedEx. optimise routes, minimise emissions & maximise efficiency!"\
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
