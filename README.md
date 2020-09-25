# BITBNS REST API ENDPOINTS

  
  <b>Get Tickers</b>
  <pre>curl -H "X-BITBNS-APIKEY: ${API-KEY}" -X GET 'https://api.bitbns.com/api/trade/v1/tickers'</pre>
  <pre>Example :: curl -H "X-BITBNS-APIKEY: 234545231CDFGGDFDFEWSD" -X GET 'https://api.bitbns.com/api/trade/v1/tickers'</pre>
 <details> 
  <summary>
   View Response
  </summary>
  <pre>
  {
  "BTC": {
    "highest_buy_bid": 482521.71,
    "lowest_sell_bid": 484900,
    "last_traded_price": 484900,
    "yes_price": 478854.88,
    "volume": {
      "max": 486925.39,
      "min": 476001,
      "rate": "482521.71",
      "volume": 9.02210891
    }
  },
  "XRP": {
    "highest_buy_bid": 38.11,
    "lowest_sell_bid": 38.18,
    "last_traded_price": 38.18,
    "yes_price": 38.73,
    "volume": {
      "max": 41.54,
      "min": 37.52,
      "volume": 1585075.17
    }
  },
  "NEO": {
    "highest_buy_bid": 1322.5,
    "lowest_sell_bid": 1326,
    "last_traded_price": 1322,
    "yes_price": 1350.16,
    "volume": {
      "max": 1379,
      "min": 1318,
      "volume": 411.1436
    }
  },
  "GAS": {
    "highest_buy_bid": 382.5,
    "lowest_sell_bid": 390.99,
    "last_traded_price": 382.5,
    "yes_price": 374,
    "volume": {
      "max": 390.53,
      "min": 370.02,
      "volume": 1113.1023
    }
  },
  "ETH": {
    "highest_buy_bid": 15840,
    "lowest_sell_bid": 16043,
    "last_traded_price": 15800,
    "yes_price": 16149.11,
    "volume": {
      "max": 16229.38,
      "min": 15774,
      "volume": 168.8011
    }
  },
  "XLM": {
    "highest_buy_bid": 18.26,
    "lowest_sell_bid": 18.31,
    "last_traded_price": 18.57,
    "yes_price": 18.45,
    "volume": {
      "max": 18.79,
      "min": 18.17,
      "volume": 244062.39
    }
  },
  "RPX": {
    "highest_buy_bid": 0.91,
    "lowest_sell_bid": 0.92,
    "last_traded_price": 0.92,
    "yes_price": 0.92,
    "volume": {
      "max": 0.94,
      "min": 0.88,
      "volume": 127176.16
    }
  },
  "DBC": {
    "highest_buy_bid": 0.54,
    "lowest_sell_bid": 0.55,
    "last_traded_price": 0.55,
    "yes_price": 0.57,
    "volume": {
      "max": 0.58,
      "min": 0.54,
      "volume": 795890.91
    }
  },
  "LTC": {
    "highest_buy_bid": 4213,
    "lowest_sell_bid": 4250,
    "last_traded_price": 4250,
    "yes_price": 4348.99,
    "volume": {
      "max": 4349,
      "min": 4150,
      "volume": 72.3038
    }
  },
  "XMR": {
    "highest_buy_bid": 8310,
    "lowest_sell_bid": 8995,
    "last_traded_price": 8300.01,
    "yes_price": 9000,
    "volume": {
      "max": 9000,
      "min": 8300.01,
      "volume": 0.4373
    }
  },
  "DASH": {
    "highest_buy_bid": 13880.01,
    "lowest_sell_bid": 14100,
    "last_traded_price": 14100,
    "yes_price": 13799,
    "volume": {
      "max": 14488,
      "min": 13799,
      "volume": 20.2756
    }
  },
  "DOGE": {
    "highest_buy_bid": 0.41,
    "lowest_sell_bid": 0.43,
    "last_traded_price": 0.42,
    "yes_price": 0.42,
    "volume": {
      "max": 0.43,
      "min": 0.41,
      "volume": 954109
    }
  },
  "BCH": {
    "highest_buy_bid": 37000,
    "lowest_sell_bid": 38750,
    "last_traded_price": 38992,
    "yes_price": 33300,
    "volume": {
      "max": 39489,
      "min": 32300,
      "volume": 21.1112
    }
  },
  "SC": {
    "highest_buy_bid": 0.44,
    "lowest_sell_bid": 0.45,
    "last_traded_price": 0.45,
    "yes_price": 0.45,
    "volume": {
      "max": 0.46,
      "min": 0.44,
      "volume": 1997981
    }
  },
  "TRX": {
    "highest_buy_bid": 1.55,
    "lowest_sell_bid": 1.58,
    "last_traded_price": 1.58,
    "yes_price": 1.57,
    "volume": {
      "max": 1.61,
      "min": 1.55,
      "volume": 1238965
    }
  },
  "ETN": {
    "highest_buy_bid": 1.19,
    "lowest_sell_bid": 1.2,
    "last_traded_price": 1.2,
    "yes_price": 0.96,
    "volume": {
      "max": 1.22,
      "min": 0.96,
      "volume": 14710856.2
    }
  },
  "ONT": {
    "highest_buy_bid": 136,
    "lowest_sell_bid": 137,
    "last_traded_price": 136.1,
    "yes_price": 132.8,
    "volume": {
      "max": 138.14,
      "min": 132.8,
      "volume": 83.59
    }
  },
  "ZIL": {
    "highest_buy_bid": 2.47,
    "lowest_sell_bid": 2.51,
    "last_traded_price": 2.51,
    "yes_price": 2.48,
    "volume": {
      "max": 2.54,
      "min": 2.43,
      "volume": 70498
    }
  },
  "EOS": {
    "highest_buy_bid": 402.01,
    "lowest_sell_bid": 419.98,
    "last_traded_price": 402.01,
    "yes_price": 401.26,
    "volume": {
      "max": 424.53,
      "min": 385.02,
      "volume": 2463.57
    }
  },
  "POLY": {
    "highest_buy_bid": 12.33,
    "lowest_sell_bid": 12.75,
    "last_traded_price": 12.33,
    "yes_price": 12.02,
    "volume": {
      "max": 12.78,
      "min": 11.15,
      "volume": 22656.4
    }
  },
  "DGB": {
    "highest_buy_bid": 1.79,
    "lowest_sell_bid": 1.83,
    "last_traded_price": 1.83,
    "yes_price": 1.76,
    "volume": {
      "max": 1.83,
      "min": 1.76,
      "volume": 58500
    }
  },
  "NCASH": {
    "highest_buy_bid": 0.39,
    "lowest_sell_bid": 0.41,
    "last_traded_price": 0.4,
    "yes_price": 0.41,
    "volume": {
      "max": 0.42,
      "min": 0.4,
      "volume": 1567452
    }
  },
  "ADA": {
    "highest_buy_bid": 5.89,
    "lowest_sell_bid": 5.99,
    "last_traded_price": 5.89,
    "yes_price": 5.84,
    "volume": {
      "max": 6.14,
      "min": 5.84,
      "volume": 889199.8
    }
  },
  "ICX": {
    "highest_buy_bid": 50,
    "lowest_sell_bid": 52.5,
    "last_traded_price": 49.5,
    "yes_price": 49,
    "volume": {
      "max": 52.99,
      "min": 49,
      "volume": 464.11
    }
  },
  "VEN": {
    "highest_buy_bid": 0.96,
    "lowest_sell_bid": 0.98,
    "last_traded_price": 0.98,
    "yes_price": 0.95,
    "volume": {
      "max": 0.98,
      "min": 0.95,
      "volume": 26700
    }
  },
  "OMG": {
    "highest_buy_bid": 247,
    "lowest_sell_bid": 262.99,
    "last_traded_price": 247,
    "yes_price": 244.39,
    "volume": {
      "max": 269.99,
      "min": 244.39,
      "volume": 10.25
    }
  },
  "REQ": {
    "highest_buy_bid": 2.94,
    "lowest_sell_bid": 3.14,
    "last_traded_price": 3.14,
    "yes_price": 3.11,
    "volume": {
      "max": 3.14,
      "min": 2.9,
      "volume": 57599.3
    }
  },
  "DGD": {
    "highest_buy_bid": 2900,
    "lowest_sell_bid": 3400,
    "last_traded_price": 2450,
    "yes_price": 2450,
    "volume": {
      "max": 2450,
      "min": 2450,
      "volume": 0
    }
  },
  "QLC": {
    "highest_buy_bid": 4.01,
    "lowest_sell_bid": 4.36,
    "last_traded_price": 3.97,
    "yes_price": 4.37,
    "volume": {
      "max": 4.37,
      "min": 3.92,
      "volume": 1820.69
    }
  },
  "POWR": {
    "highest_buy_bid": 12.14,
    "lowest_sell_bid": 13.38,
    "last_traded_price": 13.5,
    "yes_price": 13.48,
    "volume": {
      "max": 13.79,
      "min": 12.01,
      "volume": 1678.64
    }
  },
  "WPR": {
    "highest_buy_bid": 1.55,
    "lowest_sell_bid": 1.66,
    "last_traded_price": 1.55,
    "yes_price": 1.57,
    "volume": {
      "max": 1.66,
      "min": 1.55,
      "volume": 1710.4
    }
  },
  "WAVES": {
    "highest_buy_bid": 160,
    "lowest_sell_bid": 178,
    "last_traded_price": 157,
    "yes_price": 160,
    "volume": {
      "max": 177,
      "min": 157,
      "volume": 129.69
    }
  },
  "WAN": {
    "highest_buy_bid": 68,
    "lowest_sell_bid": 74.01,
    "last_traded_price": 67.42,
    "yes_price": 67.28,
    "volume": {
      "max": 74.01,
      "min": 67.28,
      "volume": 92.34
    }
  },
  "ACT": {
    "highest_buy_bid": 2.24,
    "lowest_sell_bid": 2.38,
    "last_traded_price": 2.38,
    "yes_price": 2.25,
    "volume": {
      "max": 2.36,
      "min": 2.25,
      "volume": 2152.33
    }
  },
  "XEM": {
    "highest_buy_bid": 6.75,
    "lowest_sell_bid": 7,
    "last_traded_price": 6.8,
    "yes_price": 7,
    "volume": {
      "max": 7.35,
      "min": 6.75,
      "volume": 1153.15
    }
  },
  "XVG": {
    "highest_buy_bid": 1.03,
    "lowest_sell_bid": 1.06,
    "last_traded_price": 1.03,
    "yes_price": 1.02,
    "volume": {
      "max": 1.07,
      "min": 1.02,
      "volume": 453268.5
    }
  },
  "BLZ": {
    "highest_buy_bid": 9,
    "lowest_sell_bid": 9.28,
    "last_traded_price": 9,
    "yes_price": 8.49,
    "volume": {
      "max": 9.29,
      "min": 8.49,
      "volume": 11.46
    }
  },
  "SUB": {
    "highest_buy_bid": 8.5,
    "lowest_sell_bid": 8.8,
    "last_traded_price": 8.55,
    "yes_price": 8.2,
    "volume": {
      "max": 8.98,
      "min": 8.2,
      "volume": 765.63
    }
  },
  "LRC": {
    "highest_buy_bid": 6.57,
    "lowest_sell_bid": 7.4,
    "last_traded_price": 7,
    "yes_price": 6.94,
    "volume": {
      "max": 7.52,
      "min": 6.94,
      "volume": 193.95
    }
  },
  "NEXO": {
    "highest_buy_bid": 3.99,
    "lowest_sell_bid": 4,
    "last_traded_price": 4,
    "yes_price": 3.72,
    "volume": {
      "max": 4.01,
      "min": 3.72,
      "volume": 29046.74
    }
  },
  "EFX": {
    "highest_buy_bid": 0.64,
    "lowest_sell_bid": 0.69,
    "last_traded_price": 0.69,
    "yes_price": 0.68,
    "volume": {
      "max": 0.7,
      "min": 0.65,
      "volume": 22993.58
    }
  },
  "CPX": {
    "highest_buy_bid": 1.3,
    "lowest_sell_bid": 1.34,
    "last_traded_price": 1.3,
    "yes_price": 1.32,
    "volume": {
      "max": 1.37,
      "min": 1.3,
      "volume": 7218.03
    }
  },
  "ZRX": {
    "highest_buy_bid": 47.03,
    "lowest_sell_bid": 48.9,
    "last_traded_price": 49,
    "yes_price": 46.51,
    "volume": {
      "max": 50,
      "min": 46.51,
      "volume": 13900.62
    }
  },
  "REP": {
    "highest_buy_bid": 954,
    "lowest_sell_bid": 1175,
    "last_traded_price": 954,
    "yes_price": 950,
    "volume": {
      "max": 1175,
      "min": 950,
      "volume": 1.59
    }
  },
  "LOOM": {
    "highest_buy_bid": 6.51,
    "lowest_sell_bid": 6.92,
    "last_traded_price": 6.51,
    "yes_price": 6.95,
    "volume": {
      "max": 6.95,
      "min": 6.51,
      "volume": 200.89
    }
  },
  "EOSD": {
    "highest_buy_bid": 3.23,
    "lowest_sell_bid": 3.79,
    "last_traded_price": 3.79,
    "yes_price": 3.84,
    "volume": {
      "max": 3.84,
      "min": 3.1,
      "volume": 239.77
    }
  },
  "STORM": {
    "highest_buy_bid": 0.57,
    "lowest_sell_bid": 0.6,
    "last_traded_price": 0.57,
    "yes_price": 0.62,
    "volume": {
      "max": 0.62,
      "min": 0.6,
      "volume": 25471.63
    }
  },
  "GNT": {
    "highest_buy_bid": 10.4,
    "lowest_sell_bid": 11.59,
    "last_traded_price": 11,
    "yes_price": 10.37,
    "volume": {
      "max": 11.75,
      "min": 10,
      "volume": 3279.59
    }
  },
  "QTUM": {
    "highest_buy_bid": 262.08,
    "lowest_sell_bid": 298,
    "last_traded_price": 262.02,
    "yes_price": 288.23,
    "volume": {
      "max": 295.75,
      "min": 261,
      "volume": 60.665
    }
  },
  "QKC": {
    "highest_buy_bid": 2.96,
    "lowest_sell_bid": 3.24,
    "last_traded_price": 3.34,
    "yes_price": 3.4,
    "volume": {
      "max": 3.41,
      "min": 2.9,
      "volume": 840.8
    }
  },
  "LSK": {
    "highest_buy_bid": 240,
    "lowest_sell_bid": 255,
    "last_traded_price": 255,
    "yes_price": 259,
    "volume": {
      "max": 259,
      "min": 255,
      "volume": 1.5
    }
  },
  "NPXS": {
    "highest_buy_bid": 0.1,
    "lowest_sell_bid": 0.11,
    "last_traded_price": 0.11,
    "yes_price": 0.11,
    "volume": {
      "max": 0.11,
      "min": 0.1,
      "volume": 2839598
    }
  },
  "USDT": {
    "highest_buy_bid": 72.05,
    "lowest_sell_bid": 75,
    "last_traded_price": 72.01,
    "yes_price": 75.59,
    "volume": {
      "max": 75.59,
      "min": 72.01,
      "volume": 10081
    }
  },
  "ETC": {
    "highest_buy_bid": 806,
    "lowest_sell_bid": 839.99,
    "last_traded_price": 806,
    "yes_price": 806.01,
    "volume": {
      "max": 810.01,
      "min": 804.17,
      "volume": 28.7366
    }
  },
  "DENT": {
    "highest_buy_bid": 0.16,
    "lowest_sell_bid": 0.17,
    "last_traded_price": 0.17,
    "yes_price": 0.16,
    "volume": {
      "max": 0.17,
      "min": 0.16,
      "volume": 139919
    }
  },
  "CLOAK": {
    "highest_buy_bid": 145,
    "lowest_sell_bid": 170,
    "last_traded_price": 176,
    "yes_price": 170,
    "volume": {
      "max": 176,
      "min": 147,
      "volume": 23.72
    }
  },
  "KMD": {
    "highest_buy_bid": 79,
    "lowest_sell_bid": 86,
    "last_traded_price": 75,
    "yes_price": 86.99,
    "volume": {
      "max": 86.99,
      "min": 75,
      "volume": 3
    }
  },
  "GRS": {
    "highest_buy_bid": 35,
    "lowest_sell_bid": 43.51,
    "last_traded_price": 35,
    "yes_price": 35,
    "volume": {
      "max": 35,
      "min": 35,
      "volume": 0
    }
  },
  "RAM": {
    "highest_buy_bid": 0.53,
    "lowest_sell_bid": 0.54,
    "last_traded_price": 0.53,
    "yes_price": 0.53,
    "volume": {
      "max": 0.55,
      "min": 0.5,
      "volume": 3012453
    }
  },
  "LET": {
    "highest_buy_bid": 0.61,
    "lowest_sell_bid": 0.66,
    "last_traded_price": 0.66,
    "yes_price": 0.66,
    "volume": {
      "max": 0.66,
      "min": 0.63,
      "volume": 1276.58
    }
  },
  "SOUL": {
    "highest_buy_bid": 2.23,
    "lowest_sell_bid": 2.52,
    "last_traded_price": 2.48,
    "yes_price": 2.48,
    "volume": {
      "max": 2.48,
      "min": 2.48,
      "volume": 0
    }
  },
  "PHX": {
    "highest_buy_bid": 0.91,
    "lowest_sell_bid": 0.92,
    "last_traded_price": 0.92,
    "yes_price": 0.92,
    "volume": {
      "max": 0.94,
      "min": 0.88,
      "volume": 127176.16
    }
  },
  "VET": {
    "highest_buy_bid": 0.96,
    "lowest_sell_bid": 0.98,
    "last_traded_price": 0.98,
    "yes_price": 0.95,
    "volume": {
      "max": 0.98,
      "min": 0.95,
      "volume": 26700
    }
  },
  "TST": {
    "highest_buy_bid": 25,
    "lowest_sell_bid": 25.78,
    "last_traded_price": 25,
    "volume": {
      
    }
  }
}
   </pre>
  </details>
  

  <b>Get Platform Status</b>
  <pre>curl -H "X-BITBNS-APIKEY: ${API-KEY}" -X GET 'https://api.bitbns.com/api/trade/v1//platform/status'</pre>
  <pre>curl -H "X-BITBNS-APIKEY: 234545231CDFGGDFDFEWSD" -X GET 'https://api.bitbns.com/api/trade/v1/platform/status'</pre>
  <details> 
  <summary>
   View Response
  </summary>
  <pre>
  {
  "data": {
    "BTC": {
      "status": 1
    },
    "ETH": {
      "status": 1
    },
    "XRP": {
      "status": 1
    },
    "NEO": {
      "status": 1
    },
    "GAS": {
      "status": 1
    },
    "XLM": {
      "status": 1
    },
    "TRX": {
      "status": 1
    },
    "ADA": {
      "status": 1
    },
    "VET": {
      "status": 1
    },
    "XVG": {
      "status": 1
    },
    "BCH": {
      "status": 1
    },
    "DASH": {
      "status": 1
    }
  },
  "status": 1,
  "error": null
}
   </pre>
  </details>
  
  
  <b>Get Sell Order Book</b>
  <pre> curl -H "X-BITBNS-APIKEY: ${API-KEY}" -X GET 'https://api.bitbns.com/api/trade/v1/orderbook/sell/{$COIN_NAME}' </pre>
  <pre> Example :: curl -H "X-BITBNS-APIKEY: 234545231CDFGGDFDFEWSD" -X GET 'https://api.bitbns.com/api/trade/v1/orderbook/sell/BTC'</pre>
  <details> 
  <summary>
   View Response
  </summary>
  <pre>
  {
  "data": [
    {
      "rate": 484900,
      "btc": 4949076
    },
    {
      "rate": 484999.83,
      "btc": 6819225
    },
    {
      "rate": 485000,
      "btc": 15638352
    },
    {
      "rate": 486501,
      "btc": 10000000
    },
    {
      "rate": 487000,
      "btc": 1059334
    },
    {
      "rate": 488164.1,
      "btc": 19407
    },
    {
      "rate": 488498.14,
      "btc": 3300009
    },
    {
      "rate": 488900,
      "btc": 20458
    },
    {
      "rate": 488999.8,
      "btc": 8361398
    },
    {
      "rate": 489000,
      "btc": 1422836
    },
    {
      "rate": 489500,
      "btc": 2491600
    },
    {
      "rate": 489999,
      "btc": 100000
    },
    {
      "rate": 490000,
      "btc": 29226820
    },
    {
      "rate": 490500,
      "btc": 3493728
    },
    {
      "rate": 491000,
      "btc": 4576188
    }
  ],
  "status": 1,
  "error": null
}
   </pre>
  </details>
  
  
  <b>Get Buy Order Book</b>
  <pre> curl -H "X-BITBNS-APIKEY: ${API-KEY}" -X GET 'https://api.bitbns.com/api/trade/v1/orderbook/buy/{$COIN_NAME}' </pre>
  <pre>Example :: curl -H "X-BITBNS-APIKEY: 234545231CDFGGDFDFEWSD" -X GET 'https://api.bitbns.com/api/trade/v1/orderbook/buy/BTC'</pre>
  <details> 
  <summary>
   View Response
  </summary>
  <pre>
  {
  "data": [
    {
      "rate": 482521.71,
      "btc": 1480291
    },
    {
      "rate": 482500.05,
      "btc": 162504639
    },
    {
      "rate": 480438.54,
      "btc": 37173738
    },
    {
      "rate": 479501.1,
      "btc": 22104440
    },
    {
      "rate": 479501,
      "btc": 2407893
    },
    {
      "rate": 479500.33,
      "btc": 7917630
    },
    {
      "rate": 479500.03,
      "btc": 5227636
    },
    {
      "rate": 479500,
      "btc": 2704380
    },
    {
      "rate": 479171.9,
      "btc": 9088329
    },
    {
      "rate": 479000,
      "btc": 1159937
    },
    {
      "rate": 478900,
      "btc": 100092
    },
    {
      "rate": 477101.14,
      "btc": 7921749
    },
    {
      "rate": 477000.55,
      "btc": 7222376
    },
    {
      "rate": 476200,
      "btc": 2220391
    },
    {
      "rate": 476000,
      "btc": 14063735
    }
  ],
  "status": 1,
  "error": null
}
   </pre>
  </details>
  
  <b>Get Server Time</b>
  <pre>curl -H "X-BITBNS-APIKEY: 234545231CDFGGDFDFEWSD" -X GET 'https://api.bitbns.com/api/trade/v1/getServerTime'
</pre>

<details>
    <summary>
        View Response
    </summary>
    <pre>
    {
    "serverTime":"1538158018237",
    "status":1,
    "error":null
    }
    </pre>
</details>

<h3>How to Make POST Request via CURL</h3>
        <b>Creating Payload</b>
        <pre>
          APIKEY=234545231CDFGGDFDFEWSD
          API_SECRET_KEY=213R3S123ER4354354GGGQWECWQW
          [linux]$  echo -n '{"symbol":"/listOpenStopOrders/XRP","timeStamp_nonce":"1538388361941","body":"{\"page\":0}"}' | base64
          PAYLOAD=eyJzeW1ib2wiOiIvbGlzdE9wZW5TdG9wT3JkZXJzL1RTVCIsInRpbWVTdGFtcF9ub25jZSI6IjE1MzgzODIEWFETGRRFWEQWDCETBGRTawqfe=
        </pre>
        <b>Creating Signature Using HMAC SHA512 DGST OPENSSL</b>
        <pre>
          [linux]$ echo -n $PAYLOAD | openssl dgst -sha512 -hmac $API_SECRET_KEY
          SIGNATURE=1ff7dafdf71e9084ed09e7bd75c4a4152b26534acb5fccwbb1ea74a1db5ec9f6df04f439740e6e32ec82c5efewfetrbytwefrgrasb81ad049b0e0288
         </pre>
         <b>Curl Command</b>
         <pre>
         curl -H "X-BITBNS-APIKEY: $APIKEY" \
         -H "X-BITBNS-PAYLOAD: $PAYLOAD" \
         -H "X-BITBNS-SIGNATURE: $SIGNATURE" \
         -H "Accept: application/json" \
         -H "Accept-Charset: utf-8" \
         -H "content-type: application/x-www-form-urlencoded" \
         -X POST 'https://api.bitbns.com/api/trade/v1/listOpenStopOrders/XRP' \
         -d '{"page":0}' 
         </pre>
    <code>Note 1 :: If Query Contains Multiple Parameters then use -d '{"quantity":40,"rate":25}' and at the of creating Payload use body as {\"quantity\":40,\"rate\":25}</code><br>   
    <code>Note 2 :: If Query Contains No Parameters then use -d '{}' and at the of creating Payload use body as {}</code> 
<h4>General EndPoints</h4>
<b>listOpenStopOrders</b>
<pre>https://api.bitbns.com/api/trade/v1/listOpenStopOrders/BTC</pre>
<b>currentCoinBalance</b>
<pre>https://api.bitbns.com/api/trade/v1/currentCoinBalance/BTC</pre>
<b>placeBuyOrder</b>
<pre>https://api.bitbns.com/api/trade/v1/placeBuyOrder/BTC</pre>
<b>depositHistory</b>
<pre>https://api.bitbns.com/api/trade/v1/depositHistory/BTC</pre>
<b>buyStopLoss</b>
<pre>https://api.bitbns.com/api/trade/v1/buyStopLoss/BTC</pre>
<b>sellStopLoss</b>
<pre>https://api.bitbns.com/api/trade/v1/sellStopLoss/BTC</pre>
<b>getCoinAddress</b>
<pre>https://api.bitbns.com/api/trade/v1/getCoinAddress/BTC</pre>
<b>getApiUsageStatus</b>
<pre>https://api.bitbns.com/api/trade/v1/getApiUsageStatus/USAGE</pre>
<b>withdrawHistory</b>
<pre>https://api.bitbns.com/api/trade/v1/withdrawHistory/BTC</pre>
<b>placeSellOrder</b>
<pre>https://api.bitbns.com/api/trade/v1/placeSellOrder/BTC</pre>
<b>cancelOrder</b>
<pre>https://api.bitbns.com/api/trade/v1/cancelOrder/BTC</pre>
<b>orderStatus</b>
<pre>https://api.bitbns.com/api/trade/v1/orderStatus/BTC</pre>
<b>orderStatus</b>
<pre>https://api.bitbns.com/api/trade/v1/cancelStopLossOrder/BTC</pre>


<h2>HTTP error status codes </h2>
<h3> HTTP error codes would be returned incase of any errors, the body will also cointain an error feild which will explain the cause of the error</h3>
<div id ="HTTP_error_code_table" style ="border:1px solid">
  <table style = "width:100%">
    <tr>
      <th>Code</th>
      <th>Meaning</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
    </tr>
    <tr>
      <th>200</th>
      <th>null -- requested action has been performed without any problems </th>
    </tr>
    <tr>
      <th>400</th>
      <th>Invalid Request -- Invalid request format</th>
    </tr>
    <tr>
      <th>401</th>
      <th>authentication -- Not authorised or invalid API key</th>
    </tr>
    <tr>
      <th>403</th>
      <th>Undefined -- this request is forbidden</th>
    </tr>
    <tr>
      <th>404</th>
      <th>Exchange not found -- Unable to find exchange</th>
    </tr>
    <tr>
      <th>406</th>
      <th>Coin name not supplied or not yet supported -- coin name applied is incorrect</th>
    </tr>
    <tr>
      <th>409</th>
      <th>parameter type not correct -- parameters entered is incorrect</th>
    </tr>
    <tr>
      <th>412</th>
      <th>Oops ! Cancellation failed. Something went wrong ! -- Unable to cancel order</th>
    </tr>
    <tr>
      <th>413</th>
      <th>volume asked not acceptable -- Desired volume is not within bounds</th>
    </tr>
     <tr>
      <th>416</th>
      <th>Oops ! Not sufficient balance to purchase currency -- wallet balance is not sufficient </th>
    </tr>
     <tr>
      <th>417</th>
      <th>Oops ! Order doesn't exist any more -- Order has alredy been deleted</th>
    </tr>
     <tr>
      <th>428</th>
      <th>Price seems Irregular from current market price. -- Entered price is more than current price</th>
    </tr>
         <tr>
      <th>500</th>
      <th>Problem with our servers, try again later</th>
    </tr>
         <tr>
      <th>503</th>
      <th>currently down for maintaince</th>
    </tr>
    </tr>
  </table>
</div>