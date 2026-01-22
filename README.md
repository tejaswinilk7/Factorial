<html>
<head>
  <title>Factorial</title>
</head>
<body>

<script>
  let num = prompt("Enter a number to calculate its factorial:");

  num = Number(num);

  if (num < 0 || isNaN(num)) {
    alert("Invalid input! Please enter a positive number.");
  } else {
    let factorial = 1;

    for (let i = 1; i <= num; i++) {
      factorial = factorial * i;
    }

    alert("The factorial of " + num + " is " + factorial);
  }
</script>

</body>
</html>
