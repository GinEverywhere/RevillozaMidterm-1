# RevillozaMidterm-1
Midterm Requirement 1 - Reflection Narrative Data Privacy &amp; CyberSec
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reflection on Data Privacy and Cybersecurity</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <script src="https://pyscript.net/latest/pyscript.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #fff; 
            background-color: #800000; /* Perpetual maroon color */
            padding: 20px;
            text-align: center;
            font-family: 'Georgia', serif; 
            font-size: 2.5em; 
            border-radius: 8px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }
        p {
            line-height: 1.6;
        }
        .highlight {
            background-color: #e9ecef;
            padding: 10px;
            border-left: 4px solid #800000; /* Maroon left border */
        }
        .input-section {
            margin-top: 20px;
            padding: 10px;
            border: 1px solid #800000; /* Maroon border */
            border-radius: 5px;
            background-color: #f0f0f0;
        }
        button {
            background-color: #800000; /* Maroon button */
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #600000; /* Darker maroon on hover */
        }
    </style>
</head>
<body>

<h1>Reflection on Data Privacy and Cybersecurity</h1>
<p>In today’s digital landscape, safeguarding personal data is paramount. The <strong>Data Privacy Act of 2012</strong> in the Philippines was a significant step toward addressing concerns about how personal information is collected, processed, and protected. However, despite the existence of these laws, Filipinos face a surge in cyber threats. During the recent <strong>Data Privacy and Awareness Campaign</strong>, I discovered the various cybersecurity risks prevalent in the country, including phishing scams, love scams, sextortion, email extortion, ransomware, cyberbullying, and gambling-related scams.</p>

<p class="highlight">Phishing scams are among the most widespread threats encountered by Filipinos. These scams deceive individuals into revealing sensitive information such as passwords or bank details through seemingly legitimate emails or messages. The trick lies in the scammers' ability to create realistic-looking communications that can easily mislead unsuspecting victims. The campaign emphasized the importance of vigilance—always verify the source of emails before clicking any links.</p>

<p>Love scams prey on vulnerable individuals, often targeting those seeking companionship on dating apps or social media platforms. Scammers build emotional connections with their victims before requesting money under false pretenses, leading to severe financial and emotional distress. This campaign highlighted the need for skepticism in online relationships and stressed the importance of never sending money to someone met online, especially if the request seems urgent.</p>

<p class="highlight">Sextortion and email extortion present another level of danger. In sextortion cases, victims face threats of having explicit images shared unless they pay a ransom. Email extortion follows a similar pattern but revolves around personal information instead of explicit content. The emotional toll of these scams can be devastating. The key takeaway is to avoid sharing sensitive content online and to report suspicious messages to authorities.</p>

<p>Ransomware, a form of malicious software, has also become a concern. It locks users out of their devices until a ransom is paid. The campaign advised against downloading files from unverified sources and encouraged regular backups to protect essential data. Staying informed about potential threats and employing antivirus software can significantly mitigate the risk of ransomware attacks.</p>

<p class="highlight">Cyberbullying is an issue that continues to grow, particularly among students. Harassment on social media platforms can lead to significant emotional distress. The campaign urged individuals to report and block bullies and emphasized the importance of educating students about responsible online behavior.</p>

<p>Additionally, with the rise of online gambling, many Filipinos have fallen victim to scams involving fake casinos that steal personal information or refuse to pay winnings. Participants were reminded to engage only with licensed platforms to ensure the safety of their personal and financial data.</p>

<p>Overall, the <strong>Data Privacy and Awareness Campaign</strong> highlighted the myriad cyber threats facing Filipinos today. While the <strong>Data Privacy Act of 2012</strong> offers some protection, individual responsibility and awareness are vital in securing our data and digital presence. By implementing stronger security measures, staying cautious in online interactions, and being vigilant against phishing tactics, each of us can contribute to a safer digital environment.</p>

<div class="input-section">
    <h2>Your Thoughts on Data Privacy</h2>
    <textarea id="userInput" rows="4" cols="50" placeholder="Share your thoughts on data privacy..."></textarea><br>
    <button onclick="submitInput()">Submit</button>
    <p id="output"></p>
</div>

<py-script>
def submit_input(input_text):
    return f"You shared: {input_text}"

def submitInput():
    input_text = Element("userInput").value
    output_text = submit_input(input_text)
    Element("output").element.innerHTML = output_text
</py-script>

</body>
</html>
