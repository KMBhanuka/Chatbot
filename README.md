<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Vegetable Store</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        function addToCart(vegetable) {
            alert(vegetable + " added to cart!");
        }
    </script>
</head>
<body>
    <header class="bg-success text-white text-center py-3">
        <h1>Online Vegetable Store</h1>
    </header>
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-4">
                <div class="card text-center">
                    <img src="carrot.jpg" class="card-img-top" alt="Carrot">
                    <div class="card-body">
                        <h5 class="card-title">Carrot</h5>
                        <p class="card-text">$2.50 per kg</p>
                        <button class="btn btn-success" onclick="addToCart('Carrot')">Add to Cart</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card text-center">
                    <img src="tomato.jpg" class="card-img-top" alt="Tomato">
                    <div class="card-body">
                        <h5 class="card-title">Tomato</h5>
                        <p class="card-text">$1.80 per kg</p>
                        <button class="btn btn-success" onclick="addToCart('Tomato')">Add to Cart</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card text-center">
                    <img src="broccoli.jpg" class="card-img-top" alt="Broccoli">
                    <div class="card-body">
                        <h5 class="card-title">Broccoli</h5>
                        <p class="card-text">$3.00 per kg</p>
                        <button class="btn btn-success" onclick="addToCart('Broccoli')">Add to Cart</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>

