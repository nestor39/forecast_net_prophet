# Forecast 
This code was created with the purpose of figuring out if the ability to predict search traffic can translate into the ability to successfully trade stock, with some help from Google Colab and Prophet forecasting at scale from facebook.

## Technologies
```
pandas
holoviews 
fbprophet 
hvplot.pandas
datetime
%matplotlib inline
```

## Installation

In order to open and run this program you have to follow these steps:

* Go to my repository in GitHub and open the repository called ```forecast_net_prophet_11```

* Copy the repository's link.

![forecast_net_prophet_ssh](https://user-images.githubusercontent.com/80844686/121765219-38e57d80-cafe-11eb-89a0-a8cbc27c228d.jpeg)


* Open Git Bash in your computer.

![git_bash](https://user-images.githubusercontent.com/80844686/115638940-40d82c80-a2c8-11eb-816a-e991b245cd88.jpg)

* Clone the repository by typing ```git clone``` and paste the link ``` git@github.com:nestor39/forecast_net_prophet_11.git ```.

![git_clone_forecast_net_11](https://user-images.githubusercontent.com/80844686/121765210-24a18080-cafe-11eb-8264-9b5c48e05f68.jpg)


After doing the steps above you are going to have the files in your computer, now we are going to need to open it and for that we have two options: 

The first option is going to be through Git Bash:
 * Open Git Bash in your computer.
  
  * Activate  the Conda development environment, by typing ```conda activate dev```.
  
 * Type  ```jupyter lab"``` in your Git Bash(it will open a tab in your explorer).
  
 * Open the file ```forecasting_net_prophet.ipynb``` and you are going to be able to see the code.

The second option is going to be through Google Colab
  * Open Google Colab by clicking in this link https://colab.research.google.com/notebooks/intro.ipynb#recent=true . 
  
  ![upload_colab](https://user-images.githubusercontent.com/80844686/121765292-ad202100-cafe-11eb-9340-e7da5633fe96.jpg)

  
  * Upload the file ```file forecasting_net_prophet.ipynb``` 
  
  * Install the the next libraries:
  ```
from IPython.display import clear_output
try:
  !pip install pystan
  !pip install fbprophet
  !pip install hvplot
  !pip install holoviews
except:
  print("Error installing libraries")
finally:
  clear_output()
  print('Libraries successfully installed')
  ```
  
https://user-images.githubusercontent.com/80844686/121765668-697ae680-cb01-11eb-83d6-f11168d2499f.mp4


  
  * Run the code.
  

## Results

This code is going to show you many superpower tools with interactive characteristics:


https://user-images.githubusercontent.com/80844686/121765818-6d5b3880-cb02-11eb-818f-e9397d191a48.mp4



https://user-images.githubusercontent.com/80844686/121765831-89f77080-cb02-11eb-8594-ae9b2e16c6f1.mp4


https://user-images.githubusercontent.com/80844686/121765840-94b20580-cb02-11eb-949b-b3ba6ecf75f2.mp4



https://user-images.githubusercontent.com/80844686/121765849-a5627b80-cb02-11eb-8bad-12b1252108a5.mp4




Additional step 5:


https://user-images.githubusercontent.com/80844686/121765618-1d2fa680-cb01-11eb-81dd-5f8e8b6d384d.mp4




## Examples

![forecast_net_prophet_excalidraw](https://user-images.githubusercontent.com/80844686/121763729-21ed5e00-caf3-11eb-9e9d-5c213c016c50.jpeg)


## Contributors

This project was made with helpful contribuitions from Berkeley Fintech Bootcamp members; Siege and Joel Gonzales. Joel Gonzales was of particular assistence when it came to improving the code.

I also utilized the AskBCS Learning Assistent in order to fine-tune my project.

This code was written by Nestor Ramirez.

email: nestorramirez3994@gmail.com

Linkedin: (https://www.linkedin.com/in/nestor-ramirez-cuadro-375654209/)


## License
MIT
