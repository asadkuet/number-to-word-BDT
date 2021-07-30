# number-to-word-BDT
This will convert any integer or decimal number to words. It's based on the number system used in Bangladeshi currency BDT.
Example: If you call the function AmountInWord(12345), it will give you output: "Twelve Thousand Three Hundred and Forty Five Taka only"

Just follow the steps to convert numbers to words:
1. Clone & include the "amountInWords.js" in your application.
2. Call the function "AmountInWord" as bellow:
       AmountInWord(12345);
   This will return: "Twelve Thousand Three Hundred and Forty Five Taka only"

3. For fractional rounding use like this:
       AmountInWord( Math.round(123456.789 * 100) / 100);
   This will return: "One Lac Twenty Three Thousand Four Hundred and Fifty Six Taka and Seventy Nine paisa only"

4. And use this for rounding to integer value:
       AmountInWord( Math.round(123456.789) );
   This will return: "One Lac Twenty Three Thousand Four Hundred and Fifty Seven Taka only"
   
Just It! Now, you will get your desired Amount in Words
