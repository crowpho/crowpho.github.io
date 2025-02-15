<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personalized Valentine's Card</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffcccb;
            font-family: 'Courier New', monospace;
            flex-direction: column;
        }
        .card {
            text-align: center;
            position: relative;
        }
        .button {
            font-size: 18px;
            margin: 10px;
            padding: 10px;
            cursor: pointer;
            border: none;
            background-color: #ff6666;
            color: white;
            border-radius: 5px;
        }
      .popup {
        display: none;
        position: fixed;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        background: white;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
        text-align: center;
        max-height: 400px; /* Set a max height */
        overflow-y: auto; /* Enable vertical scrolling */
        width: 300px; /* Adjust width if needed */
       }
        }
        .spotify {
            margin-top: 20px;
        }
    </style>
    <script>
        function showPopup(id) {
            document.getElementById(id).style.display = 'block';
        }
        function closePopup(id) {
            document.getElementById(id).style.display = 'none';
        }
    </script>
</head>
<body>
    <div class="card">
        <h2>💌 NOTICE 💌</h2>
        <p>To: the prettiest girl in the world ♡<br>From: ur secret lover</p>
        <button class="button" onclick="showPopup('giftPopup')">📜 Read me ♡</button>
        <div id="giftPopup" class="popup">
            <p>happy Valentine's Day honey~ i know everything has been so hectic but you mean the world to me. I love u so so so much. I don't know what I'd do without u and spending time with you is the most relaxing and fun thing I could ever do. ILYSM HONEY you're amazing and you deserve the best. ILYSM~ ❤️</p>
            <button class="button" onclick="closePopup('giftPopup')">Close</button>
        </div>
        
        <h3>things I love about you~ ♡</h3>
        <button class="button" onclick="showPopup('lovePopup')">💖 Open ♡</button>
        <div id="lovePopup" class="popup">
            <p>1. you save stuff for me u know i'll be interested in.</p>
            <p>2. your empathy is so sweet and light on the heart.</p>
            <p>3. you're so strong--no matter what you've went through, you pushed through and continue to be kind. that's something that takes effort.</p>
            <p>4. you're always telling me to rest and so understanding when school gets hectic.</p>
            <p>5. you are so passionate about helping others and self-growth.</p>
            <p>6. you're patient with me. i could be stuck and frustrated ab something and yet u don't get irritated ab it.</p>
            <p>7. you notice small details.</p>
            <p>8. you trust me enough to open up to me.</p>
            <p>9. your talent for customization in games. idk how u do it babe.</p>
            <p>10. you update me with your little snaps. i love them sm~.</p>
            <p>11. you always do your best to stay up with me even when i get there late. i love u so much baby i know it's not easy.</p>
            <p>12. you're so creative when making our worlds and characters.</p>
            <p>13. you can always make something silly and cheer me up.</p>
            <p>14. when u say "i love you" all of a sudden it makes me so happy~</p>
            <p>15. you always send vids for our characters~.</p>
            <p>16. you're so selfless and considerate of others, even those that hurt you.</p>
            <p>17. you're picky ab food and i think it's so cute hehe~</p>
            <p>18. your art never fails to make me smile, not once.</p>
            <p>19. your voice is the cutest thing ever and i love hearing it.</p>
            <p>20. you make mc skins for me even when ur tired after making ur own.</p>
            <p>21. i love your style so much, so cute and soft on the eyes~</p>
            <p>22. you always make me feel like i matter.</p>
            <p>23. your silly random "meow" when u make the bots.</p>
            <p>24. i'm never bored when i get to be with you.</p>
            <p>25. you're always so sincere when you speak.</p>
            <p>26. you tell me how you're feeling and are so open.</p>
            <p>27. you don't make me feel like i'm overreacting about stuff while reassuring me.</p>
            <p>28. you let me talk ab my interests even when u don't have a clue what i'm going on ab.</p>
            <p>29. you laugh at my jokes.</p>
            <p>30. you're so cute and the best thing that ever happened to me.</p>
            <p> </p>
            <p> hehe... OTHER 70 COMING SOON BABY I LOVE YOU SO SO SO SO MUCH BABY I LOVE YOU MUAH~ HAPPY VALENTINES DAY MY DARLING I LOVE UUUU~</p>
            <button class="button" onclick="closePopup('lovePopup')">Close</button>
        </div>
        
        <div class="spotify">
            <iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/6jgkEbmQ2F2onEqsEhiliL?utm_source=generator" width="300" height="80" frameborder="0" allowfullscreen allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"></iframe>
        </div>
    </div>
</body>
</html>
