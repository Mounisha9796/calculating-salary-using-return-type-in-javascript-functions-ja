<!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<button onclick="EmployeeDetails('sana','ibm','30000')">complete details</button>
<p id="SAP"></p>
<script>
function EmployeeDetails(name,Companyname,salary){
document.getElementById("demo").innerHTML= "Welcome " + name + ", the " + Companyname + "." + salary;
}

</script>
</body>
</html>
