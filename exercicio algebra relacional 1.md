a) select model from PC where PC.speed >= 3.00;
π model (σ PC.speed ≥ 3 (PC))

b) select Product.maker from Product, Laptop where Product.model = Laptop.model and Laptop.hd >= 100;
π Product.maker σ Product.model = Laptop.model and Laptop.hd ≥ 100 ( Product ⨯ Laptop )