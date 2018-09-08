# DA_Assignment4.3
1. States = rownames(US Arrests)
Get states names with ‘w’.
>States[grep('w', States)]
[1] "Delaware"      "Hawaii"        "Iowa"          "New Hampshire"
[5] "New Jersey"    "New Mexico"    "New York"  
Get states names with ‘W’.
> States[grep('W', States)]
[1] "Washington"    "West Virginia" "Wisconsin"     "Wyoming"      
2. Prepare a Histogram of the number of characters in each US state.
>h<-nchar(States)

>h

>hist(h, col = 'blue')
