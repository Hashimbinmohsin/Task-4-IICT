# Task 4 IICT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Victoria's Journal</title>
    <style>
        body {
            background-color: #ddeaea;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 40px 0;
        }
        #container {
            background: #f7fdfe;
            width: 780px;
            margin: 0 auto;
            border: 8px solid #e6f3f3;
            border-radius: 5px;
            padding: 8px 8px 30px 8px;
        }
        #header {
            background: #abeaea;
            border: 4px solid #eefcfc;
            padding: 18px;
            text-align: right;
            margin-bottom: 10px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        #title {
            font-size: 2.3em;
            color: #34bfc8;
            font-weight: normal;
            letter-spacing: 1px;
        }
        #subtitle {
            font-size: 1.1em;
            color: #77c9cf;
            font-weight: lighter;
            display: block;
        }
        #main-content {
            display: flex;
            flex-direction: row;
            align-items: flex-start;
        }
        #friends-box {
            width: 180px;
            min-height: 140px;
            background: #8be2e2;
            border: 4px solid #2dbfcc;
            border-radius: 5px;
            padding: 14px 15px;
            font-family: 'Segoe UI', Verdana, Geneva, Tahoma, sans-serif;
            margin-right: 20px;
            float: left;
        }
        #friends-box h3 {
            color: #1e7e92;
            font-size: 1.35em;
            margin-top: 0;
            font-weight: normal;
            margin-bottom: 10px;
        }
        #friends-list {
            padding-left: 20px;
            margin: 0;
        }
        #friends-list li {
            color: #405961;
            margin-bottom: 4px;
        }
        #friends-list li span {
            font-weight: 600;
            color: #e83d71;
        }
        .journal-entries {
            width: 100%;
        }
        .entry {
            background: #e6f3f3;
            border: 3px solid #c9e4ea;
            border-radius: 4px;
            margin-bottom: 22px;
            padding: 14px 14px 14px 14px;
            overflow: auto;
        }
        .entry-title {
            color: #40b8c4;
            font-size: 1.32em;
            font-weight: bold;
            margin-bottom: 8px;
            display: block;
            letter-spacing: .5px;
        }
        .entry-date {
            color: #1e8caf;
            font-size: 1.08em;
            font-weight: bold;
            margin-right: 3px;
        }
        .entry-text {
            color: #858585;
            font-size: 1.1em;
            float: left;
            width: 65%;
        }
        .entry-img {
            float: right;
            max-width: 30%;
            margin-left: 20px;
        }
        .entry-img img {
            width: 100%;
            height: auto;
            border: 2px solid #a8d2da;
            border-radius: 3px;
        }
        /* Responsive (optional) */
        @media (max-width: 900px) {
            #container { width: 98%; }
        }
        @media (max-width: 600px) {
            #main-content { flex-direction: column; }
            #friends-box { margin-right: 0; margin-bottom: 20px; float: none; }
            .journal-entries { width: 100%; }
            .entry-text, .entry-img { float: none; width: 100%; margin-left: 0; }
        }
    </style>
</head>
<body>
    <div id="container">
        <div id="header">
            <span id="title">Victoria's Journal</span><br>
            <span id="subtitle">So fresh and so clean</span>
        </div>
        <div id="main-content">
            <div id="friends-box">
                <h3>Friends</h3>
                <ul id="friends-list">
                    <li><span>390 Buddies</span></li>
                    <li><span>Big Will</span></li>
                    <li><span>Conan the Librarian</span></li>
                </ul>
            </div>
            <div class="journal-entries">
                <div class="entry">
                    <span class="entry-title">
                        <span class="entry-date">04/09/08:</span> Spatulas
                    </span>
                    <div class="entry-text">
                        Yesterday, I went to the store and got some much needed spatulas! (what better way to say I love myself than to buy myself a spatula?)
                    </div>
                    <div class="entry-img">
                        <img src="https://cdn.pixabay.com/photo/2017/03/28/12/10/spatula-2188530_1280.png" alt="spatula">
                    </div>
                    <div style="clear: both;"></div>
                </div>
                <div class="entry">
                    <span class="entry-title">
                        <span class="entry-date">04/08/08:</span> Cookie Cupcakes
                    </span>
<div class="entry-text">
                        My favorite cartoon character is cookie, and my favorite dessert is cupcakes. So Cookie Cupcakes are best of both the worlds. Did you know? Cookie character once said, "Sometimes me think what is love, and then me think love is what cookie is for. Me give up the last cookie for you." I wonder if the same applies for the cupcakes? (If so, I don't think I can ever love ANYONE!)
</div>
<div class="entry-img">
<img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=380&q=80" alt="cookie cupcakes">
</div>
<div style="clear: both;"></div>
</div>
</div>
</div>
</div>
</body>
</html>

