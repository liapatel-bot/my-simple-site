# my-simple-site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StyleCut Salon | Premium Haircuts & Appointments</title>
    <style>
        :root {
            --gold: #ffd700;
        }
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: #1a1a1a;
            color: #eee;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(#2c2c2c, #111);
            padding: 2rem 0;
            text-align: center;
        }
        nav {
            background: #111;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            color: var(--gold);
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://source.unsplash.com/random/1600x900/?barber,haircut') center/cover no-repeat;
            height: 80vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .hero h1 {
            font-size: 3.5rem;
            margin: 0;
        }
        section {
            padding: 60px 20px;
            max-width: 1200px;
            margin: auto;
        }
        h2 {
            text-align: center;
            color: var(--gold);
            margin-bottom: 40px;
        }
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }
        .service {
            background: #222;
            padding: 25px;
            border-radius: 10px;
            text-align: center;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }
        .gallery img {
            width: 100%;
            border-radius: 8px;
        }
        .btn {
            background: var(--gold);
            color: #111;
            padding: 14px 32px;
            text-decoration: none;
            border-radius: 
