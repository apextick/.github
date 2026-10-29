# ApexTick — Institutional-Grade Market Data, Excel Add-Ins & MCP Server

[**Platform (`apextick.com`)**](https://apextick.com) · [**Interactive Docs (`docs.apextick.com`)**](https://docs.apextick.com) · [**Starter `.xlsx` Workbook**](https://grid.apextick.com/templates/ApexTick-Starter-and-Test-Suite.xlsx) · [**Live Status**](https://apextick.com/status)

ApexTick is an ultra-low latency market data normalization engine and financial intelligence platform covering **66,400+ global equities, ETFs, FX pairs, and cryptocurrencies**, historical OHLCV candles, technical indicators (`RSI14`, `MACD`, `SMA`, `EMA`, `ATR14`, `RVOL20`), company fundamentals, ETF tearsheets & holdings, **Options Chains with pre-calculated Greeks**, and **16,700+ macroeconomic series**.

### Core Products

1. **Normalized REST & Event-Driven WebSocket API (`https://api.apextick.com`):**
   * Consolidated market snapshots, active intraday pricing, deep historical series, and monotonically sequenced WebSocket feeds (`/v1/market/stream`).
2. **`ApexTick Excel Lite` & `ApexTick Excel Native` (`https://docs.apextick.com/excel`):**
   * 17 dynamic-array formulas (`=APEXTICK.QUOTE`, `=APEXTICK.STREAM`, `=APEXTICK.OPTIONS.CHAIN`, `=APEXTICK.FINANCIALS`, `=APEXTICK.INDICATOR`) with vectorized multi-symbol evaluation on Excel for the Web, Mac, and Windows.
3. **Hosted Streamable HTTP MCP Server (`https://api.apextick.com/mcp`):**
   * Connect Claude Desktop, Claude Code, Claude.ai Web/iOS, Cursor, and OpenCode in one command (`get_quote`, `analyze_ticker`, `explain_price_move`, `get_watchlist_brief`, `screen_market`).
4. **Instant Multi-Channel Alerts & Automated Community Digests:**
   * Price, technical (`RSI`, `MACD` cross), and 20-day Relative Volume (`rvol20`) alerts + scheduled Pre-Market (`08:30 ET`) and Closing Bell (`16:30 ET`) briefings for Discord, Telegram, Slack, Email, and Signed Webhooks.
