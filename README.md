The jupyter notebook is to check if the two PUBG maps have different playstyles. The initial hypothesis is that Erangel has longer kill distances over Miramar due to more cover existing in Erangel, allowing for longer distance fighting. This hypothesis is common among players.

The results for the two maps are:
The average distance of a kill on Erangel : 141.3505695541631m
The average distance of a kill on Miramar : 131.11430721222413m

The t-test resulted in a p-value < .01, meaning that the kill distance is different. 

The problem didnt stop there. The distances seemed a little too high, and upon further inspection of the data, there were kills that spanned 11.2km (with the largest distance on the map is 11.4km). This meant that hackers could be skewing the data. Upon researching the maximum distance a player model will display is a little under 1km. Any kill above 1km was considered hacking and removed from the analysis (this doesn't remove all hacked kills, but it removes the ones that players couldn't physically pull off). 


The results for the two maps after cleaning are:
The average distance of a kill on Erangel without hackers: 27.837347602965085
The average distance of a kill on Miramar without hackers: 26.10129790279316

The t-test resulted in a p-value < .01, meaning that the kill distance is different. 

There are two takeaways to this results. The first takeaway is there are quite a bit of impossible kills logged, and the second is that even though the kill distance difference is statistically significant, the difference of 1.7m does not provide a significance in terms of how gameplay changes. 
