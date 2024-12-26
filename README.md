<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="SPACE RACE CHASE">
    <meta name="keywords" content="Mailboxes, Mailbox, NASA, CIA, Space Shuttles, JFK">
    <meta name="author" content="Empty Engineering">
    <title>Government</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: radial-gradient(rgb(0, 0, 0), rgb(0, 0, 50), rgb(0, 0, 100));
            color: #fff;
            line-height: 1.6;
        }

        header {
            text-align: center;
            background: rgb(0, 190, 205);
            padding: 20px;
        }

        header h1 {
            font-size: 2rem;
            color: rgb(10, 2, 12);
            margin: 0;
        }

        .lazer {
            padding: 20px;
        }

        .lazer p {
            font-size: 1rem;
        }

        ol {
            text-align: left;
            color: #bfc000;
            background: url('https://www.architecturalmailboxes.com/wp-content/uploads/2015/05/home-featured-3.jpg') no-repeat;
            background-size: cover;
            padding: 10px;
            list-style-position: inside;
        }

        a {
            text-align: center;
            display: block;
            margin: 20px 0;
        }

        a img {
            max-width: 100%;
            height: auto;
            border: none;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            text-align: center;
        }

        table th, table td {
            border: 1px solid #fff;
            padding: 10px;
        }

        table th {
            background: #333;
        }

        .nasa {
            text-align: center;
            padding: 20px;
        }

        .nasa h3, .nasa p, .nasa h5 {
            margin: 10px 0;
        }

        .web-information-cia {
            padding: 20px;
        }

        .web-information-cia h2, .web-information-cia h4, .web-information-cia h6 {
            margin: 10px 0;
        }

        .decischoice {
            background: #fff;
            color: #000;
            padding: 20px;
            text-align: center;
        }

        .decischoice label, .decischoice input, .decischoice select, .decischoice a {
            display: block;
            margin: 10px auto;
            max-width: 300px;
        }

        .decischoice input {
            width: calc(100% - 20px);
            padding: 5px;
        }

        .decischoice a {
            text-decoration: none;
            background: #007BFF;
            color: #fff;
            padding: 10px;
            border-radius: 5px;
            display: inline-block;
        }

        .decischoice a:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>USPS</h1>
    </header>

    <main>
        <section class="lazer">
            <p>The USPS has many types of mailboxes, the USPS is owned by the government.</p>
            <hr>
            <aside>
                <ol type="I">
                    <li>Modern</li>
                    <li>Rustic</li>
                    <li>Victorian</li>
                    <li>Invisible</li>
                </ol>
            </aside>
        </section>

        <section>
            <a href="https://en.wikipedia.org/wiki/Letter_box" target="_blank">
                <img src="http://doctoroddjob.com/communities/4/000/000/218/564//images/698902.jpg" alt="Mail box">
            </a>
            <table>
                <thead>
                    <tr>
                        <th></th>
                        <th>Modern</th>
                        <th>Rustic</th>
                        <th>Victorian</th>
                        <th>Invisible</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <th>Looks good</th>
                        <td>Yes</td>
                        <td>Yes</td>
                        <td>Yes</td>
                        <td>No</td>
                    </tr>
                    <tr>
                        <th>Useful</th>
                        <td>Yes</td>
                        <td>Yes</td>
                        <td>Yes</td>
                        <td>No</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section class="nasa">
            <h3>Then we go to NASA</h3>
            <a href="https://www.nasa.gov/" target="_blank">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRCBYycm791j-fgPOVFx08I6DQXtr28dssvAMp5A7_Lz8xctMQe" alt="NASA Logo">
            </a>
            <p>NASA no longer uses space shuttles.</p>
            <h5>NASA has a 24/7 live stream of the International Space Station.</h5>
            <iframe width="560" height="315" src="https://www.ustream.tv/embed/17074538?html5ui" allowfullscreen></iframe>
            <p>The ISS travels at a speed of around 4 miles per second!</p>
        </section>

        <section class="web-information-cia">
            <h2>CIA</h2>
            <div>
                <p>The Central Intelligence Agency is a civilian foreign intelligence service of the United States federal government, tasked with gathering, processing, and analyzing national security information.</p>
                <h4>Controversy</h4>
                <p>The CIA is encircled in conspiracy theories from the cause of 9/11 to JFK's assassination.</p>
                <h6>Founded</h6>
                <p>The CIA was founded in 1947.</p>
                <a href="http://www.cia.gov" target="_blank">Visit the CIA</a>
            </div>
        </section>

        <section class="decischoice">
            <label for="sel1">Choose Your Favourite</label>
            <select id="sel1">
                <option>USPS</option>
                <option>NASA</option>
                <option>CIA</option>
            </select>
            <label for="input1">And tell us why:</label>
            <input id="input1" type="text" placeholder="Your reason here">
            <a href="#">Submit Report</a>
        </section>
    </main>
</body>
</html>
