<!DOCTYPE html>
<html>
<p>Create a script that collects numbers from a page and then adds them up and prints them to a blank field on the page.</p><hr><br>
<label for = "answer"> SUM OF THE NUMBERS: </label>
<input type = "text" id = "answer"/>
<script>
let sum = 0;
const nums = [];
let n = parseInt(prompt("enter the size"));
function sumnums(){
for(let i = 0; i < n; i++){
nums[i] = parseInt(prompt("enter the num"));
sum = sum + nums[i];
}
return sum;
}
document.getElementById("answer").value = sumnums();
</script>
</html>
