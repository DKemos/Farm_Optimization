# Farm_Optimization

The Farrow family owns and operates a 640 acre farm that has been in the family for many generations. They enjoy their self-reliant lifestyle and are determined to maintain their tradition of successfully living off the land, during an era when many family farms have been taken over by large agricultural corporations. John and Eunice Farrow manage the farm, and their three older children also work on the farm. 

The entire family can produce a total of 4,000 person hours worth of labour during the winter and spring months, and 4,500 person hours during the summer and autumn months. If any of these person-hours are not needed, the children work on neighbouring farms for which they are paid £5 per hour during the winter and spring and £5.50 per hour during the summer and autumn.

The farm supports two types of livestock – dairy cows and egg laying hens, as well as three crops – soybeans, corn, and wheat. All three crops are sold for cash, but corn is also used to feed the cows, and some wheat is used to feed the hens. The family has to decide the mix of livestock and crops for the coming year.

Currently, the family has saved £20,000, which they can invest. They currently own 30 cows valued at £35,000, and 2,000 hens valued at £5,000. They wish to keep all this livestock and maybe buy more. Each new cow would cost £1,500, and each new hen costs £3. Over a one-year time, the value of the herd of cows will decrease by 10% and hens by 25% due to aging. 
Each cow requires 2 acres of land for grazing and 10 person-hours of work per month, while producing a net annual income of £850. Hens require no significant space, 0.05 person-hours of work per month, and produce a net annual income of £4.25 each. The hen house can hold at most 5,000 hens, and the barn limits the size of the cowherd to 42. 
For each acre planted in each of the three crops, the following table gives the number of person-hours of work that will be required during the first and second halves of the year:

---------------- Soybeans	    Corn	         Wheat
Winter & Spring	  1.0                0.9	          0.6
Summer & Autumn	  1.4                1.2	          0.7

Data is person-hours per acre planted.

To provide food for the livestock, the family needs to plant at least 1 acre of corn for each cow and 0.05 acres of wheat for each hen. This will provide food for the entire year. 

The family are deciding how much acreage should be planted in each of the crops and how many cows and hens to have for the coming year. Their objective is to maximise the familys monetary worth at the end of the year (the sum of the net income from their livestock plus the net value of the crops plus what remains of the livestock fund plus the value of the livestock plus any additional earnings from neighbouring farms minus their living expenses of £40,000). 
The weather being uncertain affects the net value per acre of the planted crops. The table below details the various effects of the weather scenarios on the net value per acre planted of each crop.

-----------------Net value per acre planted
----------------Soybeans	Corn	Wheat
Drought	        -£10		-£15	£0
Flood		£15		£20	£10
Good		£70		£60	£50

Formulate and solve a linear programming model and find a plan that maximises the family’s wealth for each weather scenario using XPressMP. State the optimal plan under each scenario. Given the family does not know what weather scenario will actually happen and that they need to decide a plan in advance of knowing the weather, suggest how they might determine what to do.


## Build With
* [XpressMP](http://www.fico.com/en/products/fico-xpress-optimization) - Optimization Tool
