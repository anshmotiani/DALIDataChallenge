# DALIDataChallenge

I created a few visualizations but my favorite ones were 

1) the stacked bar chart that detailed the percentage of total items per segment by subcategory. I thought there would be a difference in the types of goods people bought for Consumer, Corporate, and Home Office, but I was surprised to find out that wasn’t the case. The percentage distributions were almost identical which was fascinating.
2) Total sale value by state. I wanted to create a choropleth map because those are always a challenge. It took me a few hours to figure it out but I got there eventually. I was happy with how it turned out.
3) After creating the state choropleth map, I wanted to challenge myself to do it by county. I took in the zipcodes and found a CSV online that had corresponding FIP codes. I created a new dataframe with these codes and the total sale value by county, and then I graphed it. It was really interesting to see certain counties completely outspend everyone else.


Using plotly turned out to be a great choice because I could make all of the graphs interactive. I feel like that really elevates a user’s experience because they can play around with the visualization in whatever way that they want. It’s almost like having many different visualizations in one.


I was pretty disappointed by my regression neural network. I couldn’t find much correlation in the various attributes. I thought delivery time would be something cool to look at, but it was almost solely determined by the shipping method and it would also be all over the place. If I had more time to work on this data challenge, I’d definitely spend more time on the second part of this challenge.


I learned a lot about choropleth maps while working on this challenge because those were the most difficult to work with. I had to learn about fip codes, geojson files, etc. It was a fun process overall!
