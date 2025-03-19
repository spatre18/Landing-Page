<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chatpati Chaat Recipes</title>
    <style>
        body { 
            font-family: Arial, sans-serif; 
            margin: 0; 
            padding: 0; 
            box-sizing: border-box;
            background: linear-gradient(to right, #ffecd2, #fcb69f);
        }
        .header { 
            background-color: #ff7e5f; 
            color: #fff; 
            text-align: center; 
            padding: 20px; 
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        .section { 
            display: flex; 
            flex-wrap: wrap; 
            justify-content: center; 
            gap: 20px; 
            padding: 30px;
        }
        .recipe-card { 
            width: 300px; 
            border-radius: 15px; 
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); 
            background-color: #fff; 
            overflow: hidden; 
            transition: transform 0.3s ease-in-out;
        }
        .recipe-card:hover {
            transform: scale(1.05); 
        }
        .recipe-card img { 
            width: 100%; 
            height: 200px; 
            object-fit: cover; 
        }
        .recipe-card h3 { 
            background-color: #ff4500; 
            color: #fff; 
            margin: 0; 
            padding: 10px; 
            display: flex; 
            align-items: center; 
            justify-content: center; 
        }
        .recipe-card h3 img { 
            width: 25px; 
            height: 25px; 
            margin-right: 8px; 
        }
        .recipe-card p { 
            padding: 10px; 
            color: #555; 
        }
        .cta { 
            background-color: #ff4500; 
            color: #fff; 
            padding: 10px 20px; 
            border: none; 
            border-radius: 20px; 
            cursor: pointer; 
            margin-top: 10px; 
        }
        .cta:hover { 
            background-color: #e63e00; 
        }

        .footer {
            background-color: #de8f19;
            color: #fff;
            text-align: center;
            padding: 15px 0;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>😋 Special Jain Chatpati Chaat Recipes 🍽️</h1>
        <p>Discover the secret Jain recipes of your favorite street-style chaats!</p>
    </div>

    <div class="section">
        <div class="recipe-card">
            <img src="c:\Users\Sakshi\Downloads\panipuri_logo-removebg-preview.png" alt="Pani Puri">
            <h3>Pani Puri</h3>
            <p>Crunchy puris with spicy tangy water for the ultimate street food delight!</p>
            <button class="cta">View Recipe</button>
        </div>

        <div class="recipe-card">
            <img src="c:\Users\Sakshi\Downloads\istockphoto-1428926221-170667a-removebg-preview.png" alt="Dahi Puri">
            <h3>Dahi Puri</h3>
            <p>Creamy, tangy, and spicy—Dahi Puri is a burst of flavors in every bite!</p>
            <button class="cta">View Recipe</button>
        </div>

        <div class="recipe-card">
            <img src="c:\Users\Sakshi\Downloads\images__2_-removebg-preview.png" alt="Ragada Samosa">
            <h3>Ragada Samosa</h3>
            <p>Delicious samosa drenched in spicy ragada curry, garnished with chutneys!</p>
            <button class="cta">View Recipe</button>
        </div>

        <div class="recipe-card">
            <img src="c:\Users\Sakshi\Downloads\Kutchi-Dabeli-8.webp" alt="Dabeli">
            <h3>Dabeli</h3>
            <p>A spicy, sweet, and tangy snack filled with flavorful potato masala!</p>
            <button class="cta">View Recipe</button>
        </div>

        <div class="recipe-card">
            <img src="c:\Users\Sakshi\Downloads\Bambayya_Pav_bhaji.jpg" alt="Pavbhaji">
            <h3>Pavbhaji</h3>
            <p>Try Our Delicious Pav Bhaji Recipes!</p>
            <button class="cta">View Recipe</button>
        </div>
    </div>
    <div class="footer">
        &copy; 2025 Recipe Sharing Platform | Designed by Sakshi Patre
    </div>
</body>
</html>
