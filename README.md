<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pricing Page</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Pricing Page</h1>
  </header>
  <main>
    <section class="pricing-table">
      <div class="plan">
        <h2>Basic</h2>
        <p>$10/month</p>
        <ul>
          <li>Feature 1</li>
          <li>Feature 2</li>
          <li>Feature 3</li>
        </ul>
      </div>
      <div class="plan">
        <h2>Pro</h2>
        <p>$20/month</p>
        <ul>
          <li>Feature 1</li>
          <li>Feature 2</li>
          <li>Feature 3</li>
          <li>Feature 4</li>
        </ul>
      </div>
      <!-- Add more plans as needed -->
    </section>
  </main>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}

.main {
  padding: 20px;
}

.pricing-table {
  display: flex;
  justify-content: space-around;
}

.plan {
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 20px;
  text-align: center;
  width: 30%;
}

.plan h2 {
  font-size: 24px;
}

.plan p {
  font-size: 20px;
  margin-bottom: 20px;
}

.plan ul {
  list-style: none;
  padding: 0;
}

.plan ul li {
  margin-bottom: 10px;
}

@media screen and (max-width: 768px) {
  .pricing-table {
    flex-direction: column;
    align-items: center;
  }

  .plan {
    width: 80%;
    margin-bottom: 20px;
  }
}
