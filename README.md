# Diet-Optimization

This prescriptive analytics problem is to find the minimum cost diet containing the minimum required amounts of the following nutrients per day:
• calories
• calcium
• vitamin A
• riboflavin
• ascorbic acid
Minimum quantities for the above nutrients are being provided. The objective is to minimize the cost of the diet which means the minimum amount to be spent while buying the foods. The object function obtained as a result is 

Min x1 + x2 + x3 + x4 + x5 + x6 + x7 + x8 + x9

Which is subject to the following conditions

1) 44700x1 + 8400x2 + 7400x3 + 2200x4 + 2600x5 + 1100x6
+ 9600x7 + 17400x8 + 26000x9 >= 270 //Calorie
2) 2x1 + 15.1x2 + 16.4x3 + 0.2x4 + 4x5 + 2.7x7 + 3.7x8
+ 6.3x9 >= 0.07 //Calcium
3) 26000x2 + 28100x3 + 169200x4 + 7200x5 + 918400x6 +
290700x7 + 5100x8 + 39000x9 >= 0 //Vitamin A
4) 0.0333x1 + 0.0235x2 + 0.0103x3 + 0.00508x4 + 0.0045x5
+ 0.0138x6 + 0.0054x7 + 0.0382x8 + 0.0082x9 >= 0.0039
//Riboflavin
5) 0.060x2 + 0.525x4 + 5.369x5 + 2.755x6 + 1.912x7 +
0.097x9 >= 0.020 //Ascorbic Acid

IBM Lindo is used to minimizing the above objective function which will provide the minimum cost diet which fulfills the daily basic nutrition requirements.
