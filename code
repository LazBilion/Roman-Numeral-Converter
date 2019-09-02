function convertToRoman(num) {

var arr = [1000, 900, 500, 400, 100, 90, 50, 40, 10, 9, 5, 4, 1];
var roman = ["M","CM","D","CD","C","XC","L","XL","X","IX","V","IV","I"];
var x = "";

for (let index=0; index<arr.length; index++){
  while (arr[index]<=num){
    x+= roman[index];
    num-=arr[index];
  }
}
return x;

}
