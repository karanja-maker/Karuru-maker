body {
  margin: 0;
  font-family: Arial;
}

header {
  display: flex;
  justify-content: space-between;
  padding: 20px;
  background: black;
  color: white;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

.hero {
  height: 90vh;
  background: url('https://via.placeholder.com/1200x600') center/cover;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.hero button {
  padding: 10px 20px;
  border: none;
  background: gold;
  cursor: pointer;
}

.shop {
  padding: 40px;
  text-align: center;
}

.products {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.card {
  border: 1px solid #ddd;
  padding: 20px;
}

.card img {
  width: 100%;
}

.about, .contact {
  padding: 40px;
  text-align: center;
  background: #f4f4f4;
}

footer {
  text-align: center;
  padding: 20px;
  background: black;
  color: white;
}
