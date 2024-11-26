<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Favorite Recipe Challenge - Hearty Beef Stew and Creamy Samp</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff6f61;
            color: white;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 36px;
            margin: 0;
        }

        .container {
            width: 90%;
            margin: 20px auto;
        }

        .recipe-section {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .recipe-image {
            width: 100%;
            max-width: 400px;
            border-radius: 8px;
        }

        .recipe-description {
            width: 100%;
            max-width: 600px;
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .recipe-description h2 {
            font-size: 28px;
            margin-bottom: 15px;
        }

        .recipe-description ul {
            padding-left: 20px;
        }

        .recipe-description li {
            margin-bottom: 8px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .recipe-image-container {
            width: 50%;
        }

        .recipe-info-container {
            width: 50%;
        }

        @media (max-width: 768px) {
            .recipe-image-container, .recipe-info-container {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Favorite Recipe Challenge</h1>
        <p>Hearty Beef Stew and Creamy Samp</p>
    </header>

    <div class="container">
        <section class="recipe-section">
            <div class="recipe-image-container">
                <img src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/151/466/original/2_samp_and_beef_stew.jpg?1732604636" alt="Hearty Beef Stew and Creamy Samp" class="recipe-image">
            </div>

            <div class="recipe-info-container">
                <div class="recipe-description">
                    <h2>Hearty Beef Stew and Creamy Samp</h2>
                    <p>This dish is a comforting and flavorful combination of tender beef stew served with creamy samp. It's perfect for cold evenings and brings warmth and satisfaction to your meal.</p>
                    
                    <h3>Ingredients for Beef Stew:</h3>
                    <ul>
                        <li>1 kg beef (stewing cuts like chuck or brisket)</li>
                        <li>2 tablespoons vegetable oil</li>
                        <li>1 onion, chopped</li>
                        <li>3 garlic cloves, minced</li>
                        <li>2 carrots, sliced</li>
                        <li>2 potatoes, peeled and cubed</li>
                        <li>1 tablespoon tomato paste</li>
                        <li>2 cups beef broth</li>
                        <li>1 teaspoon dried thyme</li>
                        <li>Salt and pepper to taste</li>
                    </ul>

                    <h3>Ingredients for Creamy Samp:</h3>
                    <ul>
                        <li>1 cup samp (cracked hominy maize)</li>
                        <li>4 cups water</li>
                        <li>1 cup milk</li>
                        <li>1 tablespoon butter</li>
                        <li>Salt to taste</li>
                    </ul>

                    <h3>Instructions:</h3>
                    <ol>
                        <li>In a large pot, heat the oil over medium-high heat. Brown the beef on all sides.</li>
                        <li>Add the onions and garlic, and cook until softened. Stir in the tomato paste and cook for another minute.</li>
                        <li>Pour in the beef broth, add the carrots, potatoes, thyme, salt, and pepper. Bring to a boil, then reduce the heat to low and simmer for about 1-2 hours, until the beef is tender.</li>
                        <li>While the stew is cooking, rinse the samp under cold water. In a separate pot, bring water to a boil and add the samp. Reduce the heat and simmer for about 45 minutes to 1 hour until the samp is tender.</li>
                        <li>Once the samp is cooked, drain any excess water and stir in the milk and butter. Season with salt to taste.</li>
                        <li>Serve the beef stew hot with a generous portion of creamy samp. Enjoy!</li>
                    </ol>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>Created by Your Name | Favorite Recipe Challenge</p>
    </footer>

    <script>
        // Optional JavaScript for interactivity (e.g., a simple alert for the user)
        document.addEventListener('DOMContentLoaded', function() {
            alert("Welcome to the Favorite Recipe Challenge: Hearty Beef Stew and Creamy Samp!");
        });
    </script>
</body>
</html>
