# Green_Stocks-Analytics
2017 vs 2018 Stock Performance

There is a vast change in the 2017 performance of Green Stocks vs 2018. Only 2 of the 12 stocks, ENPH and RUN produced a positive ROI in both years. Many of the stocks also experiences a decline in volume.

Steve should look at both economic and industry related influences before advising his parents on their investment decision. They may be better off looking at another industry.

Now lets see if the workbook can handle increasing the number of stocks analyzed.

Execution time

Improving the efficiency of the code was minimal at best! Execution time varied very little from 0.8320313 seconds to 0.8359375 seconds for 2017, and, 0.8203125 to 0.8320313 for 2018.

Execution time for 2017 Original Coding

![Original 2017](https://user-images.githubusercontent.com/95458216/147981178-fd7faca5-02ca-4286-b0dd-944ce9693717.png)

Execution time for 2017 Refactored Coding

![Refactored 2017](https://user-images.githubusercontent.com/95458216/147981201-dcde1867-131e-40ce-a978-66a4d455dcac.png)

Execution time for 2018 Original Coding

![Original 2018](https://user-images.githubusercontent.com/95458216/147981210-ee4bff0a-edbe-4d9a-8407-e33e2e278543.png)

Execution time for 2018 Refactored Coding

![Refactored 2018](https://user-images.githubusercontent.com/95458216/147981213-56547aa9-0a79-4fb8-85da-c4e72156921d.png)

Summary

Advantages of refactoring code

I found no obvious advantage of refactoring code. Possibly I have done something wrong? Execution time was actually fractionaly longer.

Disadvantages of refactoring code

A huge risk with refactoring is that your errors may destroy an already working code. It is highly recommended that you save your original code and any changes you make frequently in case you run into any issues. That way you can always go back a step without needing to start completely over. I personally ran into issues during refactoring and found that using the msgBox script, as well as, testing performance outputs individually helped me identify what was driving my errors.
