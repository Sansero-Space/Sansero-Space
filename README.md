<!DOCTYPE html>
<html lang="da">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sansero Space – Mind, Body & Soul</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f1ea;
            color: #333;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #8a7f64;
            padding: 20px;
            color: white;
            font-size: 24px;
        }
        section {
            padding: 20px;
        }
        .services {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .service {
            background: white;
            padding: 15px;
            margin: 10px;
            border-radius: 10px;
            width: 80%;
            max-width: 400px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .contact-form {
            margin-top: 20px;
        }
        input, textarea, button {
            width: 80%;
            padding: 10px;
            margin: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #8a7f64;
            color: white;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sansero Space</h1>
        <p>Mind, Body & Soul</p>
    </header>
    <section>
        <h2>Velkommen</h2>
        <p>Sansero Space er din oase for balance, ro og velvære.</p>
    </section>
    <section class="services">
        <h2>Vores Behandlinger</h2>
        <div class="service">
            <h3>Aromaterapi Massage</h3>
            <p>Blid massage med essentielle olier – 60 min. / 500 kr.</p>
        </div>
        <div class="service">
            <h3>Afslappende Massage</h3>
            <p>Dybdegående afspænding – 60 min. / 450 kr.</p>
        </div>
    </section>
    <section>
        <h2>Book en Tid</h2>
        <p><a href="https://calendly.com/" target="_blank">Klik her for booking</a></p>
    </section>
    <section class="contact-form">
        <h2>Kontakt Os</h2>
        <form>
            <input type="text" placeholder="Dit navn" required>
            <input type="email" placeholder="Din e-mail" required>
            <textarea placeholder="Din besked" rows="4" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
</body>
</html>
