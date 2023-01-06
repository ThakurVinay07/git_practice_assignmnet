let str="naman"
let bag=""
for(let i=str.length-1;i>=0;i--)
{
   bag+=str[i]
}

if(str==bag)
{
console.log("Pallindrome")
}
else
{
console.log("Not Pallindrome")
}