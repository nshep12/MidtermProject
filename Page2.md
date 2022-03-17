# MidtermProject
INFOTEC1000-Midterm Project
# Page 2 [Page 3](Page3.md) [Home](README.md)
## Some other thoughts

**[StackOverflow](https://stackoverflow.com/)** has become one of my favorite resources in learning how to design and write code. Some of the things I see on there make 
me realize just how little I know on the subject. I am constantly humbled by how much this information builds on itself. As I learn and understand more of what 
is asked of this field, I get more and more excited for the future. I struggled more than I care to admit through life and software is a means to make the biggest 
difference I can in my future. 
I *love* the comfort that brings. 

This is the most rewarding block of code I have written so far:
```
public SalesLevel GetSalesLevel(){
            SalesLevel salesLevel = SalesLevel.Bronze;
            if(this.sales >= 10000.00 && this.sales <= 19999.99 ){
                salesLevel = SalesLevel.Silver;
            }else if(this.sales >= 20000.00 && this.sales <= 29999.99){
                salesLevel = SalesLevel.Gold;
            }else if(this.sales >= 30000.00 && this.sales <= 39999.99){
                salesLevel = SalesLevel.Diamond;
            }else if(this.sales > 40000.00){
                salesLevel = SalesLevel.Platinum;
            }
            return salesLevel;
        }
```        
This code was part of a project I submitted this week in 2040. It is pretty simple logic to get specific Sales Levels to print out based on the information given. 
I was able to write this without thinking about it but I wrote it one time with no errors and it ran perfectly on the first try. I have never experienced this 
in programming so it was a big moment for me. 

I also enjoyed learning about **FizzBuzz**:

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i < 100; i++) {
		displayHTML += "<p>" + i + "</p>";
	}
	display.innerHTML = displayHTML;
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
