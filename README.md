# HARVESTIFY 🌿
#### A simple ML based website which recommends the best crop to grow and fertilizers to use on your crops.

- Farming is one of the major sectors that influences a country’s economic growth. 

- In country like India, majority of the population is dependent on agriculture for their livelihood. Many new technologies, such as Machine Learning is being implemented into agriculture so that it is easier for farmers to grow and maximize their yield. 

- In this project, I present a website in which the following applications are implemented; Crop recommendation and Fertilizer recommendation respectively. 

    - In the crop recommendation application, the user can provide the soil data from their side and the application will predict which crop should the user grow. 
    
    - For the fertilizer recommendation application, the user can input the soil data and the type of crop they are growing, and the application will predict what the soil lacks or has excess of and will recommend improvements. 
    
    
## DATA SOURCE 📊
- [Crop recommendation dataset ](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset) (custom built dataset)
- [Fertilizer suggestion dataset](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv) (custom built dataset)
- [Disease detection dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

# Built with 🛠️
● HTML
● CSS
● Bootstrap
● Javascript
● Python
● Flask
● Pandas
● Numpy
● Matplotlib
● Seaborn
● Sklearn
● Git
● AWS EC2 Cloud
● Putty
● WinScp

## DEPLOYMENT 🚀

#### This website is deployed at [AWS](https://aws.amazon.com/)
#### You can access it [here](http://ec2-3-86-195-199.compute-1.amazonaws.com:8080/)
#### Note: The website may take a minute to load sometimes, as the server may be in hibernate state

## How to use 💻
- Crop Recommendation system ==> enter the corresponding nutrient values of your soil, state and city. Note that, the N-P-K (Nitrogen-Phosphorous-Pottasium) values to be entered should be the ratio between them. Refer [this website](https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm) for more information.
Note: When you enter the city name, make sure to enter mostly common city names. Remote cities/towns may not be available in the [Weather API](https://openweathermap.org/) from where humidity, temperature data is fetched.

- Fertilizer suggestion system ==> Enter the nutrient contents of your soil and the crop you want to grow. The algorithm will tell which nutrient the soil has excess of or lacks. Accordingly, it will give suggestions for buying fertilizers.

<details>
  <summary>Supported crops
</summary>

- Apple
- Blueberry
- Cherry
- Corn
- Grape
- Pepper
- Orange
- Peach
- Potato
- Soybean
- Strawberry
- Tomato
- Squash
- Raspberry
</details>
