[macdonoughsite.html](https://github.com/user-attachments/files/24413264/macdonoughsite.html)body {
  margin: 0;
  font-family: sans-serif;
  background-image: url('https://picsum.photos/1920/1080?grayscale');
  background-size: cover;
  background-attachment: fixed;
  background-position: center;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.main-content {
  background-color: rgba(255, 255, 255, 0.8);
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  max-width: 90%;
  margin: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.page-title {
  color: #333;
  text-align: center;
  margin-top: 0;
  margin-bottom: 20px;
  font-size: 2.5em;
}

.gallery-container {
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  overflow-x: auto;
  gap: 20px;
  padding-bottom: 10px;
}

.gallery-container img {
  min-width: 300px;
  height: 200px;
  object-fit: cover;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s ease-in-out;
  flex-shrink: 0;
}

.gallery-container img:hover {
  transform: scale(1.03);
}[style.css](https://github.com/user-attachments/files/24413265/style.css)

<!doctype html>
<html>
  <head>
    <title>MacDonough Woodworks</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="main-content">
      <h1 class="page-title">MacDonough Woodworks</h1>
      <div class="gallery-container">
        <img src="https://picsum.photos/id/237/300/200" alt="A dog looking up">
        <img src="https://picsum.photos/id/238/300/200" alt="A cat sleeping">
        <img src="https://picsum.photos/id/239/300/200" alt="A river in the mountains">
        <img src="https://picsum.photos/id/240/300/200" alt="A city skyline at night">
        <img src="https://picsum.photos/id/241/300/200" alt="Mountains and a lake">
        <img src="https://picsum.photos/id/242/300/200" alt="Forest path">
      </div>
    </div>
    <script src="script.js"></script>
  </body>
</html>
