<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://unpkg.com/axios/dist/axios.min.js"></script>

</head>
<body>
<script>
axios.get('https://jsonplaceholder.typicode.com/todos/1')
  .then(res => console.log(res.data))
</script>
</body>
</html>
