<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio for Visual Storytelling in Album Covers</title>
    <script type="text/javascript" src="https://www.x3dom.org/download/x3dom.js"></script>
    <link rel="stylesheet" type="text/css" href="https://www.x3dom.org/download/x3dom.css">
</head>
 
    <style>
       @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Playfair+Display:wght@700&display=swap');
	   
        body {
            margin: 0;
            padding: 0;
            font-family: 'Helvetica', sans-serif;
            background-color: #f4f4f4;
            color: #333;
			overflow-x: hidden;
        }
        
		header {
            background-color: #1A2B4C;
            color: white;
            padding: 20px;
            text-align: center;
            position: relative;
        }

        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            margin: 0;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

       nav {
            margin-top: 15px;
        }

        nav a {
            font-family: 'Montserrat', sans-serif;
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-size: 1.2rem;
        }

        nav a:hover {
            color: #FF6F61;
        }
		

nav {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
}

.dropdown {
    position: relative;
    display: inline-block;
}

.submenu {
    display: none;
    position: absolute;
    top: 100%; /* Directly below the parent item */
    left: 0;
    background-color: #1A2B4C;
    padding: 10px 0;
    border-radius: 5px;
    min-width: 150px;
    text-align: left;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
    z-index: 10;
}

.submenu li {
    list-style: none;
}

.submenu li a {
    display: block;
    color: white;
    text-decoration: none;
    padding: 10px 20px;
    font-family: 'Montserrat', sans-serif;
    transition: background-color 0.3s;
}

.submenu li a:hover {
    background-color: #FF6F61;
}

.dropdown:hover .submenu {
    display: block;
}

.dropdown:hover .submenu,
.submenu:hover {
    display: block;
}

.dropdown .submenu {
    margin-top: -1px;
}

        .hero {
            background: linear-gradient(rgba(26, 43, 76, 0.7), rgba(26, 43, 76, 0.7)), 
            url('images/Screenshot 2024-10-08 225027.png') center/cover no-repeat;
            height: 75vh;
            padding: 100px 20px;
            text-align: center;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }


        .hero h1 {
            font-family: 'Playfair Display', serif;
            font-size: 4rem; 
            margin-bottom: 20px;
			z-index: 1;
        }

        .hero p {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.5rem;
            max-width: 700px;
            margin: 20px;
			z-index: 1;
        }
		
		.hero p1 {
            font-family: 'Playfair Display', sans-serif;
            font-size: 1.5rem;
            max-width: 700px;
            margin: 20px;
			z-index: 1;
        }

        .explanation {
			height: 85vh;
            padding: 50px 20px;
            text-align: center;
			display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            background-color: #f9f9f9;
        }

        .explanation h2 {
            font-family: 'Montserrat', sans-serif;
            font-size: 2rem;
            color: #333;
            margin-bottom: 20px;
        }

        .explanation p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 20px auto 0 auto; 
            color: #666;
            line-height: 1.6;
        }
		
		.explanation p1 {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 20px auto 0 auto; 
            color: #666;
            line-height: 1.6;
        }


        .quick-links {
            background-color: #FCE0E3;
            padding: 50px 20px;
            text-align: center;
        }

        .quick-links h2 {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.4rem;
            margin-bottom: 30px;
            color: #333;
        }

        .quick-links .button {
            background-color: #FF6F61;
            color: white;
            padding: 15px 30px;
            margin: 10px;
            font-size: 1.2rem;
            border: none;
            border-radius: 25px;
            text-decoration: none;
            display: inline-block;
            transition: background-color 0.3s, transform 0.2s;
			    font-family: 'Montserrat', sans-serif;
        }

        .quick-links .button:hover {
            background-color: #E05650;
            transform: scale(1.05);
        }


        footer {
            background-color: #1A2B4C;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
            font-size: 1rem;
        }

    </style>
</head>
<body>

<!-- Header Section -->
    
<header>
    <nav>
        <a href="index.html">Home</a>
        <a href="abouttheproject.html">About the Project</a>
        <div class="dropdown">
            <a href="#" class="parent">Weekly Tasks</a>
            <ul class="submenu">
                <li><a href="week1.html">Week 1</a></li>
                <li><a href="week2.html">Week 2</a></li>
                <li><a href="week3.html">Week 3</a></li>
                <li><a href="week4.html">Week 4</a></li>
				  <li><a href="week5.html">Week 5</a></li>
				    <li><a href="week6.html">Week 6</a></li>
					  <li><a href="week7.html">Week 7</a></li>
					    <li><a href="week8.html">Week 8</a></li>
						  <li><a href="week9.html">Week 9</a></li>
						    <li><a href="week10.html">Week 10</a></li>
							  <li><a href="week11.html">Week 11</a></li>
            </ul>
        </div>
        <a href="reflection.html">Conclusion / Reflection</a>
    </nav>
</header>

<!-- Hero Section -->
   
   <section class="hero">
    <p>A web page design proposal on</p>
    <h1>The Art of Album Covers</h1>
    <p1>
       Visual Storytelling in Music
    </p1>
	</section>

<!-- Explanation Section -->

    <section class="explanation">
    <h2>How This Website Works</h2>
    <p>
        This website is designed to guide you through my portfolio on The Art of Album Covers - Visual Storytelling in Music. 
    </p>
	
	<p>
        Use the navigation menu at the top to explore different sections, including an introduction to the project, Independent Learning (IL) and 
		Lab tasks from Weeks 1 to 11, and a reflection section (same as the personal reflection document).
    </p>
	
	<p> 
		Each page provides a blend of written content, visuals, and reflections that showcase my progress in understanding the 
		relationship between music, culture, and design.
	</p>

	<p>
		
		If you're not sure where to start, don't worry — each page will have a link at the bottom, guiding you through a seamless, 
		step-by-step journey across the website. Simply follow along to explore the project in an easy and intuitive way!
		
	</p> 
	
    </section>

<!-- Quick Links to Weekly Analysis -->
	
    <section class="quick-links">
        <h2>Click the link below to begin exploring the project</h2>
        <a href="abouttheproject.html" class="button">About the Project</a>
    </section>

<!-- Footer Section -->

    <footer>
        <p>&copy; 2024 Initial Portfolio for The Art of Album Covers - Visual Storytelling in Music. All rights reserved.</p>
    </footer>

</body>
</html>
