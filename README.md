<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MarketFolio24</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
      <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
   
<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');

@keyframes fadeIn {
    0% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
@keyframes slideIn {
        0% {
            transform: translateY(-100%);
        }
        100% {
            transform: translateY(0%);
        }
    }
    
  keyframes fadeIn {
    0% {
        opacity: 0;
    }
    100% {
        opacity: 1;
     }
  }

}

body {
     font-family: 'Roboto', sans-serif;
     font-size: 1rem;
     line-height: 1.5;
     color: #333;
     background-color: #f5f5f5;   
     }

/* Header */
header {
    background: linear-gradient(135deg, #007bff, #6610f2);
    height: 50px;
    padding: 0.5rem 0;
    text-align: center;
}

header h1 {
    font-weight: 500;
    font-size: 2 rem;
    height: 0.5px;
    margin-bottom: 0.1rem;
    color: #fff;
    text-align: top;
}

header p {
    font-weight: 700;
    height: 50px;
    font-size: 1 rem;
    color: #fff;
}

/* Navigation */
.navbar {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    background-color: #fff;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    animation: fadeIn 0.5s ease-in-out, colorChange 0.5s ease-in-out infinite alternate;
    z-index: 1000; /* This ensures the navbar stays above other elements */
}

.navbar-brand {
    font-weight: 700;
    font-size: 1rem;
    color: #007bff;
    transition: color 0.3s;
    animation: fadeIn 0.5s ease-in-out, slideIn 1s ease-in-out;
}

.navbar-brand:hover {
    color: #6610f2;
    animation: fadeIn 0.5s ease-in-out;
}

.nav-link {
    font-weight: 400;
    font-size: 1rem;
    color: #333;
    transition: color 0.3s;
    animation: fadeIn 0.5s ease-in-out, slideIn 0.5s ease-in-out;
}

.nav-link:hover {
    color: #007bff;
    animation: fadeIn 0.5s ease-in-out;
}


/* Carousel */
.carousel .carousel-item {
    height: 200px;
    width: 400px;
}

.carousel img {
    position: absolute;
    top: 1rem;
    left: 1rem;
    min-height: 300px;
    min-width: 200%;
    max-width: none;
    width: 200%;
    object-fit: carousel-control-prev;
}

/* Content */
.container h2 {
    font-weight: 700;
    font-size: 2rem;
    margin-bottom: 1.5rem;
    animation: fadeIn 2s ease-in-out;
}

.btn-primary {
    background: linear-gradient(135deg, #007bff, #6610f2);
    border-color: transparent;
    transition: background 0.3s;
    animation: fadeIn 2s ease-in-out;
}
/* Flexbox for widgets */
.widget-container {
  position: relative; /* or 'absolute', 'fixed', 'sticky' */
  top: 10px;
  left: 20px;
}
         Font-family: Arial, sans-serif;
      }
  
      .card {
        border-radius: 25px;
        overflow: hidden;
      }
  
      .card-img-top {
        border-top-left-radius: 25px;
        border-top-right-radius: 25px;
      }
  
      .card-body {
        padding: 1rem 1.5rem;
      }
  
      .btn {
        border-radius: 50px;
      }

.btn-primary {
  background-color: #000; /* change the color to match your desired design */
  color: #fff;
  border: none;
  border-radius: 25px;
  padding: 10px 20px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}


/* Footer */
.pill-shaped-footer {
    border-radius: 50px;
    background-color: #333;
    padding: 20px;
    height: 350px;
    color: #fff;
    text-align: center;
}

footer h4 {
    font-weight: 30;
    font-size: 1rem;
    margin-bottom: 1rem;
}

footer p {
    font-weight: 30;
    font-size: 1rem;
}

footer a {
    color: #fff;
    transition: color 0.3s;
}

footer a:hover {
    color: #007bff;
}

/* Media queries */
@media (min-width: 768px) {
    header h1 {
        font-size: 1.5rem;
    }

    header p {
        font-size: 1.3rem;
    }
}

@media (min-width: 992px) {
    .carousel .carousel-item {
height: 500px;
}
 }
</style>

</head>
<body>
   <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">MarketFolio24</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                          Markets
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                          <a class="dropdown-item" href="#">Indices</a>
                          <a class="dropdown-item" href="#">Stocks</a>
                          <a class="dropdown-item" href="commodities.html">Commodities</a>
                          <a class="dropdown-item" href="#">Cryptocurrency</a>
                          <a class="dropdown-item" href="#">Currencies</a>
                          <a class="dropdown-item" href="#">ETFs</a>
                        </div>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">News</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Affiliate programs</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Academy</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink2" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                          Brokers
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink2">
                          <a class="dropdown-item" href="#">Currency Brokers</a>
                          <a class="dropdown-item" href="#">Stock Brokers</a>
                          <a class="dropdown-item" href="#">Online Brokers</a>
                          <a class="dropdown-item" href="#">Crypto Exchanges</a>
                        </div>
                    </li>
                </
ul>
</ul>
</div>
</div>
</nav>
<br>
<br>
<br>
  <!-- Header -->
    <header class="bg-primary text-white text-center py-3">
        <h5>Your Financial Information Hub</h5>
    </header>


<!-- Hero Section -->
<section class="row">
  <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="https://bpcdn.co/images/2021/06/04164505/where-are-retail-traders-trading-780x408.png">
        <div class="carousel-caption d-none d-md-block">
          <h5>Welcome to MarketFolio24</h5>
          <p>Your one-stop platform for financial markets and investment opportunities.</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="https://www.analyticsinsight.net/wp-content/uploads/2019/12/Online-Trading.png">
      </div>
      <div class="carousel-item">
        <img src="https://media--cldnry-s--nbcnews-com.cdn.ampproject.org/i/s/media-cldnry.s-nbcnews.com/image/upload/t_fit-1240w,f_auto,q_auto:best/newscms/2020_12/3279436/200322-new-york-stock-exchange-coronavirus-cs-1144a.jpg">
      </div>
      <div class="carousel-item">
        <img src="https://www.forextrading.ng/wp-content/uploads/2019/04/how-to-trade-forex.png">
      </div>
      <div class="carousel-item">
        <img src="https://www.thebalancemoney.com/thmb/WEhTMfHOfxMLbL3DL38QaFbzuSw=/750x0/filters:no_upscale():max_bytes(150000):strip_icc()/wallstreet-be6e21ad26e546dd8b015d7be5d71528.jpg">
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</section>
<br>


<!-- TradingView Widget BEGIN -->
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com/markets/" rel="noopener" target="_blank"><span class="blue-text">Markets today</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-ticker-tape.js" async>
  {
  "symbols": [
    {
      "proName": "FOREXCOM:SPXUSD",
      "title": "S&P 500"
    },
    {
      "proName": "FOREXCOM:NSXUSD",
      "title": "US 100"
    },
    {
      "proName": "FX_IDC:EURUSD",
      "title": "EUR/USD"
    },
    {
      "proName": "BITSTAMP:BTCUSD",
      "title": "Bitcoin"
    },
    {
      "proName": "BITSTAMP:ETHUSD",
      "title": "Ethereum"
    },
    {
      "description": "Tesla",
      "proName": "NASDAQ:TSLA"
    },
    {
      "description": "Gold",
      "proName": "OANDA:XAUUSD"
    }
  ],
  "showSymbolLogo": true,
  "colorTheme": "light",
  "isTransparent": false,
  "displayMode": "adaptive",
  "locale": "en"
}
  </script>
</div>
<!-- TradingView Widget END -->
<br>
<br>

<!-- Content Section 2 -->
  <div id="myCarousel" class="carousel slide card-carousel" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <div class="card">
          <img src="https://static.politico.com/03/f5/9991ed8542b8843127277ba36a5d/201006-wall-street-ap-773.jpg" class="card-img-top" alt="Image description">
          <div class="card-body">
            <h5 class="card-title">24markets</h5>
            <p class="card-text">with us a positive difference</p>
            <a href="#" class="btn btn-primary">CTA Button</a>
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <div class="card">
          <img src="https://carprices.ae/wp-content/uploads/2023/03/Lamborghini-Revuento-Front-Side-Cover.jpg" class="card-img-top" alt="Image description">
          <div class="card-body">
            <h5 class="card-title">Avatrade</h5>
            <p class="card-text">A World-Class 
            Trading Experience</p>
            <a href="#" class="btn btn-primary">CTA Button</a>
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <div class="card">
          <img src="https://www.supercars.net/blog/wp-content/uploads/2020/07/906689-scaled.jpg" class="card-img-top" alt="Image description">
          <div class="card-body">
            <h5 class="card-title">Clicktrades</h5>
            <p class="card-text"></p>Your money is safe with us</p>
            <a href="#" class="btn btn-primary">CTA Button</a>
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <div class="card">
          <img src="https://www.deccanherald.com/sites/dh/files/articleimages/2022/10/11/aiphone14pm-cov-sho-sel-1-1152416-1665475427.jpg" class="card-img-top" alt="Image description">
          <div class="card-body">
            <h5 class="card-title">Capex</h5>
            <p class="card-text">Experience the MAGIC OF TRADING </p>
            <a href="#" class="btn btn-primary">CTA Button</a>
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <div class="card">
          <img src="https://media.cntraveler.com/photos/581b8e750ee23d7b457512e9/master/w_3989,h_2655,c_limit/private-jet-tarmac-GettyImages-523476302.jpg" class="card-img-top" alt="Image description">
          <div class="card-body">
            <h5 class="card-title">Card title 5</h5>
            <p class="card-text">Card description goes here.</p>
            <a href="#" class="btn btn-primary">CTA Button</a>
                  </div>
                </div>
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
            </div>

<br>
<br>

<!-- TradingView Widget BEGIN -->
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com/symbols/AAPL/" rel="noopener" target="_blank"><span class="blue-text">Apple</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-symbol-overview.js" async>
  {
  "symbols": [
    [
      "Apple",
      "AAPL|1D"
    ],
    [
      "Google",
      "GOOGL|1D"
    ],
    [
      "Microsoft",
      "MSFT|1D"
    ],
    [
      "BINANCE:BTCUSDT|1D"
    ]
  ],
  "chartOnly": false,
  "width": "100%",
  "height": "100%",
  "locale": "en",
  "colorTheme": "light",
  "autosize": true,
  "showVolume": false,
  "showMA": false,
  "hideDateRanges": false,
  "hideMarketStatus": false,
  "hideSymbolLogo": false,
  "scalePosition": "right",
  "scaleMode": "Normal",
  "fontFamily": "-apple-system, BlinkMacSystemFont, Trebuchet MS, Roboto, Ubuntu, sans-serif",
  "fontSize": "10",
  "noTimeScale": false,
  "valuesTracking": "1",
  "changeMode": "price-and-percent",
  "chartType": "area",
  "maLineColor": "#2962FF",
  "maLineWidth": 1,
  "maLength": 9,
  "lineWidth": 2,
  "lineType": 0
}
  </script>
</div>
<!-- TradingView Widget END -->>



<!-- Footer -->
<footer class="pill-shaped-footer">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <h4>About MarketFolio24</h4>
                <p>MarketFolio24 is a leading financial information platform, dedicated to providing market insights, investment opportunities, and financial education to traders and investors around the world.</p>
            </div>
            <div class="col-md-6">
                <h4>Contact Us</h4>
                <p>Email: info@marketfolio24.com</p>
                <p>Phone: +1 (123) 456-7890</p>
            </div>
        </div>
        <div class="row">
            <div class="col-12 text-center">
                <p>&copy; 2023 MarketFolio24.com. All rights reserved.</p>
                <p><a href="#">Terms and Conditions</a> | <a href="#">Privacy Policy</a> | <a href="#">Cookie Policy</a> | <a href="#">Risk Warning</a></p>
            </div>
        </div>
    </div>
</footer>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
              <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
</body>
</html>
