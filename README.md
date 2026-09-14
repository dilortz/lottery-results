# lottery-results
‎        .numbers {
‎            display: flex;
‎            flex-wrap: wrap;
‎            gap: 10px;
‎        }
‎
‎        .number {
‎            width: 48px;
‎            height: 48px;
‎            border-radius: 50%;
‎            background: #111827;
‎            color: white;
‎            display: flex;
‎            align-items: center;
‎            justify-content: center;
‎            font-weight: bold;
‎        }
‎
‎        .previous {
‎            text-align: center;
‎            margin-top: 30px;
‎        }
‎
‎        .previous a {
‎            display: inline-block;
‎            margin: 5px;
‎            padding: 9px 14px;
‎            background: white;
‎            border-radius: 8px;
‎            text-decoration: none;
‎            color: #111827;
‎            box-shadow: 0 2px 8px rgba(0,0,0,0.08);
‎        }
‎
‎        footer {
‎            text-align: center;
‎            padding: 25px;
‎            color: #777;
‎            font-size: 13px;
‎        }
‎    </style>
‎</head>
‎
‎<body>
‎
‎<header>
‎    <h1>🎟️ Daily Lottery Results</h1>
‎    <p>Latest lottery winning numbers</p>
‎</header>
‎
‎<div class="container">
‎
‎    <div class="date">
‎        <h2>Today's Results</h2>
‎        <p>14 September 2026</p>
‎    </div>
‎
‎    <div class="card">
‎        <h3>Lottery Name</h3>
‎
‎        <div class="numbers">
‎            <div class="number">12</div>
‎            <div class="number">27</div>
‎            <div class="number">34</div>
‎            <div class="number">41</div>
‎            <div class="number">58</div>
‎        </div>
‎    </div>
‎
‎    <div class="card">
‎        <h3>Another Lottery</h3>
‎
‎        <div class="numbers">
‎            <div class="number">03</div>
‎            <div class="number">19</div>
‎            <div class="number">25</div>
‎            <div class="number">44</div>
‎            <div class="number">67</div>
‎        </div>
‎    </div>
‎
‎    <div class="previous">
‎        <h2>📅 Previous Results</h2>
‎
‎        <a href="#">13 September</a>
‎        <a href="#">12 September</a>
‎        <a href="#">11 September</a>
‎    </div>
‎
‎</div>
‎
‎<footer>
‎    © 2026 Daily Lottery Results
‎</footer>
‎
‎</body>
‎</html>