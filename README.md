# Stock Tracker

An Android app to practise investing with fake money. Search companies, follow live prices on interactive
candlestick charts, read company info and news, keep a watchlist, and buy and sell shares with $20,000 of virtual money.

Final project of my Multiplatform Application Development degree (DAM, 2023).

<table>
<tr>
<td><img src="Material%20empleado/Screenshot_20230522_092233.png" width="220" alt="Stock detail with candlestick chart"></td>
<td><img src="Material%20empleado/comprar.png" width="220" alt="Buying shares"></td>
<td><img src="Material%20empleado/Screenshot_20230523_101640.png" width="220" alt="App screen"></td>
<td><img src="Material%20empleado/Screenshot_20230523_101701.png" width="220" alt="App screen"></td>
</tr>
</table>

## Features

- Stock search with company details
- Interactive OHLC + volume charts (Highcharts) with time ranges
- Virtual portfolio: buy and sell with live prices and market value
- Favourites / watchlist
- Company news feed

## Architecture

- **Android client** built with Android Studio.
- **Market-data API** (`PROGRAMA-CONEXION-API/`): a Node.js + Express server that proxies the stock-data provider and serves an Angular web build.

This repository contains the API server and the app's screenshots. To run the server locally, see [`GUIA DE USO.txt`](GUIA%20DE%20USO.txt) (in Spanish).

**Stack:** Android · Node.js · Express · Angular · Highcharts
