Individual Project: Bike Sharing

Project Description:

This project is intended to rewrite the Bike Sharing analysis done in Python
for Statistical Programming to make it more performant and aligned with real
world scenarios.
This project has been created for the Advanced Python class during the Big
Data Master at IE HST.

Contribution to the project:

1. Clone the repository: "git clone https://github.com/vane1993/individual_assingment.git"
2. Fork the repo on GitHub to your personal account
3.Add your fork as a remote: go to the fork of your repository and cd to your clone
" git remote add your-github-username fork-url.
4. Checkout master: "git checkout master".
5. Create a new branch : "git checkout -b branchName"
6. Make changes and commit them: "git add filename" / "git commit -m addcomment"
7.Push up your changes: "git push your-github-username branch-name"
8. Make a pull request

Dataset Description

Both hour.csv and day.csv have the following fields, except hr which is not available in day.csv

- instant: record index
- dteday : date
- season : season (1:springer, 2:summer, 3:fall, 4:winter)
- yr : year (0: 2011, 1:2012)
- mnth : month 1 to 12
- hr : hour (0 to 23)
- holiday : weather day is holiday or not 
- weekday : day of the week
- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
- weathersit : 
	- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
	- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
	- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
	- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. 
- atemp: Normalized feeling temperature in Celsius. The values are divided to 50.
- hum: Normalized humidity. The values are divided to 100.
- windspeed: Normalized wind speed. The values are divided to 67.
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes 





