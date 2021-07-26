
### google_analytics_EDA_sample

To play with data, change path to your google-cloud credentials json file.
___
Move to directory with env.yml to install dependencies.

  ``` conda env create -f environment.yml ```

### This repo contains EDA on go0gole analytics sample(20170801)
Key insights:


1. Consumer distribution by country. Major clients are located in USA/India/Europe
2. We looked closer at consumer distribution by state in USA. California(Google Headquartes Mountain View) biggest region by revenue, but it turned out that 1 customer(outlier) spent significatly more money.
3. Consumer buying trends are different in Illinois/California. Need more observations to say for sure. 
*  There was no national holidays to explain difference between consumer busket in Illinois and LA those day.
* Hypotesis1: Seasonal temperature in California was pretty high in August,1(33 degree) comparing to previous days. So people ordered more (Drinkware) category items.
* Hypotesis2: There are several top-universisties in California(UCLA,Berkeley, Stanford etc.), so people bought more (Notebook/Journals) - items for recording notes.
* Hypotesis3: There is a Business environment with top companies in California. So people tend to buy more (Office) category products.
* Hypotesis4: Google probably has different fillings for their stores according to reasons listed above.
