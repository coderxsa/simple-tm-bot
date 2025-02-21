<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple TM Bot - README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
            padding: 20px;
            margin: 0;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        code {
            background: #eee;
            padding: 2px 6px;
            border-radius: 4px;
            font-family: Consolas, monospace;
        }
        pre {
            background: #272822;
            color: #f8f8f2;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        ul, ol {
            padding-left: 20px;
        }
        hr {
            border: none;
            height: 1px;
            background: #ccc;
            margin: 20px 0;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Simple TM Bot</h1>
    <p>A simple Telegram bot that runs on <strong>Termux</strong> using <strong>Node.js</strong>.</p>

    <h2>Installation</h2>

    <h3>Step 1: Install</h3>
    <p>Follow these steps to install and run the bot:</p>

    <ol>
        <li><strong>Update and upgrade</strong> your system packages:</li>
        <pre><code>pkg update -y && pkg upgrade -y</code></pre>

        <li><strong>Install Node.js</strong> (JavaScript runtime) and <strong>Git</strong> (version control system):</li>
        <pre><code>pkg install -y nodejs git</code></pre>

        <li><strong>Clone the GitHub repository</strong>:</li>
        <pre><code>git clone https://github.com/coderxsa/simple-tm-bot.git</code></pre>

        <li><strong>Navigate into the cloned repository</strong>:</li>
        <pre><code>cd simple-tm-bot</code></pre>

        <li><strong>Install the necessary dependencies</strong>:</li>
        <pre><code>npm install</code></pre>

        <li><strong>Run the Node.js application</strong> (replace <code>27938337</code> with your phone number to get the login code):</li>
        <pre><code>node index.js 27938337</code></pre>
    </ol>

    <hr>

    <h3>Step 2: Relink the Bot</h3>
    <p>If Termux disconnects, relink the bot by running:</p>
    <pre><code>cd simple-tm-bot
node index.js 27938337</code></pre>

    <h4>If You Removed the Linked Device:</h4>
    <ol>
        <li><strong>Clear Termux data:</strong></li>
        <p>Go to <strong>Android settings</strong> > <strong>Apps</strong> > <strong>Termux</strong> > <strong>Clear Data</strong>.</p>

        <li><strong>Reinstall the bot:</strong></li>
        <pre><code>git clone https://github.com/coderxsa/simple-tm-bot.git
cd simple-tm-bot
npm install
node index.js 27938337</code></pre>
    </ol>

    <hr>

    <h2>Notes:</h2>
    <ul>
        <li>Ensure you use the correct phone number when linking the bot.</li>
        <li>If you encounter any issues, check the repository for updates or contact support.</li>
    </ul>

    <h2>License</h2>
    <p>This project is open-source. Feel free to contribute!</p>
</div>

</body>
</html>
