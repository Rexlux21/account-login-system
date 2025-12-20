<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Bootstrap Counter App</title>

    <!-- Bootstrap CSS -->
    <link 
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" 
      rel="stylesheet"
    >
</head>
<body class="bg-light d-flex justify-content-center align-items-center vh-100">

    <div class="card text-center shadow p-4" style="width: 18rem;">
        <h1 id="count" class="display-3 fw-bold">0</h1>

        <div class="d-flex justify-content-between mt-3">
            <button id="minus" class="btn btn-danger btn-lg">−</button>
            <button id="plus" class="btn btn-success btn-lg">+</button>
        </div>

        <button id="reset" class="btn btn-secondary mt-3">Reset</button>
    </div>

    <script>
        let count = 0;

        document.getElementById("plus").onclick = () => {
            count++;
            document.getElementById("count").textContent = count;
        };

        document.getElementById("minus").onclick = () => {
            count--;
            document.getElementById("count").textContent = count;
        };

        document.getElementById("reset").onclick = () => {
            count = 0;
            document.getElementById("count").textContent = count;
        };
    </script>

</body>
</html>
