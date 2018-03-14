# Financial markets and its effect on data loss

Here is the continuation of the old project about data loss. Here we add a element to it is understanding the stock price for each of the companies mentioned in the data loss file. We also have a link where it contains a JSON file for the stock price for every company. To retreive such information you need to provide the ticker symbol for the company and it comes with data, price, start price and end price for that stock for the particular date.

http://d.yimg.com/autoc.finance.yahoo.com/autoc?query={}&region=1&lang=en

But, here our main goal is not to understand the prices over the JSON file as it is hard to understand. We would get that file to pandas in our Ipython notebook and match the correct ticker symbol with company and understand whether during the time of data loss whether the company's NSE prices went down or not. You can find the code attached in the ipynb file uploaded in this folder.

Finally using that we will predict for one company whether it is affected by the data loss using tableau. 
