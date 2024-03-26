<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Site</title>
    <style>
        /* Your existing CSS styles */
    </style>
</head>
<body>
    <header>
        <!-- Your existing header content -->
    </header>

    <div class="container">
        <section id="main">
            <!-- Your existing main content -->
        </section>
    </div>

    <footer>
        <!-- Your existing footer content -->
    </footer>

    <!-- Embedding the AI Chatbot script -->
    <script>
    !function(w, d, s, ...args){
      var div = d.createElement('div');
      div.id = 'aichatbot';
      d.body.appendChild(div);
      w.chatbotConfig = args;

      var f = d.getElementsByTagName(s)[0],
      j = d.createElement(s);
      j.defer = true;
      j.type = 'module';
      j.src = 'https://aichatbot.sendbird.com/index.js';
      f.parentNode.insertBefore(j, f);
    }(window, document, 'script', '018AD1F0-29B9-4A08-807E-2F4B122E6FD9', 'onboarding_bot');
    </script>
</body>
</html>
