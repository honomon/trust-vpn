<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WireGuard VPN</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .container {
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        h1 {
            color: #333;
        }

        #status {
            margin: 20px 0;
            padding: 10px;
            font-weight: bold;
        }

        #connectButton, #disconnectButton {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }

        #connectButton {
            background-color: #4caf50;
            color: #fff;
            border: none;
        }

        #disconnectButton {
            background-color: #f44336;
            color: #fff;
            border: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>WireGuard VPN</h1>
        <div id="status">Status: Disconnected</div>
        <button id="connectButton" onclick="connectVPN()">Connect</button>
        <button id="disconnectButton" onclick="disconnectVPN()">Disconnect</button>
    </div>

    <script>
        function connectVPN() {
            // Add your logic for connecting to the VPN here
            document.getElementById('status').innerText = 'Status: Connected';
        }

        function disconnectVPN() {
            // Add your logic for disconnecting from the VPN here
            document.getElementById('status').innerText = 'Status: Disconnected';
        }
    </script>
</body>
</html>
