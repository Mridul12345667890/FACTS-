<!-- index.html --><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>World Facts - Page 1</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body class="page1">
  <div class="container">
    <h1>Welcome to World Facts</h1>
    <p>Explore the most mind-blowing facts about our planet!</p>
    <ul>
      <li>Mount Everest grows 4mm higher every year.</li>
      <li>The Amazon rainforest produces 20% of the world's oxygen.</li>
      <li>Antarctica is the driest, windiest, and coldest continent.</li>
    </ul>
    <a href="page2.html" class="btn">More Facts</a>
  </div>
</body>
</html><!-- page2.html --><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>World Facts - Page 2</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body class="page2">
  <div class="container">
    <h1>More Amazing World Facts</h1>
    <ul>
      <li>The Sahara Desert can reach freezing temperatures at night.</li>
      <li>Iceland has no mosquitoes.</li>
      <li>There are more people living in Tokyo than in all of Canada.</li>
    </ul>
    <a href="index.html" class="btn">Back to Home</a>
  </div>
</body>
</html><!-- style.css -->body { margin: 0; font-family: 'Segoe UI', sans-serif; color: white; text-align: center; }

.container { padding: 50px; background-color: rgba(0, 0, 0, 0.6); margin: 50px; border-radius: 20px; }

.page1 { background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb') no-repeat center center/cover; height: 100vh; }

.page2 { background: url('https://images.unsplash.com/photo-1502086223501-7ea6ecd79368') no-repeat center center/cover; height: 100vh; }

h1 { font-size: 2.5rem; margin-bottom: 20px; }

ul { list-style: none; padding: 0; font-size: 1.2rem; }

li { margin: 10px 0; }

.btn { display: inline-block; margin-top: 30px; padding: 10px 20px; background-color: #00bcd4; color: white; text-decoration: none; border-radius: 10px; transition: background 0.3s ease; }

.btn:hover { background-color: #0097a7; }

