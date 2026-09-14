# Awesome Prediction Markets [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools for trading, analyzing, and building on prediction markets.

Prediction markets turn real world questions into tradable contracts, and the tooling around
them has become an ecosystem of its own: cross-venue aggregators, arbitrage scanners, wallet
analytics, data APIs, autonomous agents, and alert bots. This list collects the ones worth
knowing, across Polymarket, Kalshi, Hyperliquid, Limitless, Myriad, and the venues beside them.

---

⭐ **Featured: [Predictefy](https://predictefy.com/?utm_source=predictefy)**, the API and SDK
for all prediction market builders.

Predictefy normalizes markets, prices, order books, and trades from 17 venues like Polymarket,
Kalshi and Hyperliquid into one schema, matching equivalent markets across them to surface price
gaps, history, and trader intelligence. Integrate once, then change the venue parameter to reach
REST, WebSocket, TypeScript and Python SDKs, MCP, and SQL. A nine-venue terminal runs at
predictefy.com.

👉 **Start building:** **[docs.predictefy.com](https://docs.predictefy.com/?utm_source=predictefy)**

---

## Contents

- [AI Agents](#ai-agents)
- [Aggregators](#aggregators)
- [Alerts](#alerts)
- [Analytics](#analytics)
- [APIs](#apis)
- [Arbitrage](#arbitrage)
- [Dashboards](#dashboards)
- [Data](#data)
- [DeFi](#defi)
- [Education](#education)
- [Extensions](#extensions)
- [Funds](#funds)
- [Infrastructure](#infrastructure)
- [News](#news)
- [Official](#official)
- [Parlays](#parlays)
- [Portfolio Tracking](#portfolio-tracking)
- [Trading Bots](#trading-bots)
- [Other](#other)

## AI Agents

- [Aeon](https://github.com/aaronjmars/aeon?utm_source=predictefy) - Autonomous agent framework running on GitHub Actions that monitors Polymarket and Kalshi for probability shifts and arbitrage under the MIT license.
- [Alphascope](https://www.alphascope.app/?utm_source=predictefy) - Market intelligence platform for prediction markets, tracking probability shifts and delivering real-time trading signals.
- [Bankr](https://bankr.bot/?utm_source=predictefy) - Crypto trading agent and wallet integration for X, supporting Polymarket prediction trading and private terminal interactions.
- [Baozi MCP Server](https://www.npmjs.com/package/@baozi.bet/mcp-server?utm_source=predictefy) - Open-source MCP server enabling autonomous agents to discover, trade, and resolve Solana prediction markets using on-chain proofs.
- [Elastics](https://www.elastics.ai/?utm_source=predictefy) - Automated trading operating system providing algorithmic execution alongside integrated portfolio and risk management tools.
- [Fere AI](https://fereai.xyz?utm_source=predictefy) - Multi-agent crypto assistant combining Polymarket contract discovery, on-chain sentiment tracking, and cross-chain execution.
- [Forcazt](https://forcazt.xyz/?utm_source=predictefy) - Prediction market analytics aggregator that scans contracts to detect cross-market arbitrage opportunities and pricing inefficiencies.
- [Fraction AI](https://fractionai.xyz/?utm_source=predictefy) - Decentralized training platform where autonomous agents compete and improve using reinforcement learning within specialized simulation environments.
- [MiroShark](https://github.com/aaronjmars/MiroShark?utm_source=predictefy) - Open-source simulation where hundreds of LLM personas trade a synthetic market and post to mock social feeds, with counterfactual branching.
- [Octagon AI](https://octagonai.co/?utm_source=predictefy) - Research platform for prediction markets, generating sourced event reports with model-based forecasts and market catalyst analysis.
- [oracle3](https://github.com/YichengYang-Ethan/oracle3?utm_source=predictefy) - Autonomous trading agent for Kalshi, Polymarket, and DFlow utilizing Wang Transform pricing and constraint-based arbitrage execution under Apache 2.0.
- [Pigeon](https://pigeon.trade/?utm_source=predictefy) - Multi-platform chat terminal enabling prediction market, crypto, and equities trading across Telegram, Discord, and WhatsApp.
- [PolyClaw](https://github.com/chainstacklabs/polyclaw?utm_source=predictefy) - OpenClaw plugin providing automated Polymarket order execution and contrapositive logic for arbitrage hedge discovery.
- [Polyfactual](https://www.polyfactual.com/?utm_source=predictefy) - Narrative analysis platform combining prediction market data and social sentiment to track event truthfulness.
- [Polymarket Tips](https://polymarket.tips?utm_source=predictefy) - Social sentiment analysis platform delivering real-time social media intelligence and trade recommendations for Polymarket contracts.
- [PolyMaster](https://polymaster.io?utm_source=predictefy) - Polymarket analytics platform offering large-trader wallet tracking, predictive forecasting models, and live market intelligence.
- [PolyOracle](https://app.polyoracle.com/?utm_source=predictefy) - Consensus-based market analysis system that deploys multiple language models to evaluate high-volume Polymarket contracts.
- [PolyPulse](https://www.polypulse.tech/?utm_source=predictefy) - Chrome extension delivering real-time news analysis for Polymarket traders using automated contract detection and local data processing.
- [PolyRadar](https://www.polyradar.io/?utm_source=predictefy) - Event analysis platform aggregating multi-model forecasts, confidence scores, and source citations for active Polymarket contracts.
- [Polyseer](https://www.polyseer.xyz/?utm_source=predictefy) - Open-source research platform generating Bayesian probability estimates and evidence-backed reports for Polymarket and Kalshi contracts.
- [PolyTale](https://polytale.live/?utm_source=predictefy) - Automated Twitter intelligence bot providing real-time Polymarket research, event probability analysis, and large-holder wallet tracking.
- [Polytrader](https://www.polytrader.ai/?utm_source=predictefy) - Automated Polymarket trading platform combining model-driven analysis, strategy execution, and social sentiment signals.
- [Predictefy MCP](https://www.npmjs.com/package/@predictefy/mcp?utm_source=predictefy) - MCP server exposing normalized market data, cross-venue matching, history, and execution to agents across Polymarket, Kalshi, Hyperliquid, and other venues.
- [Predly](https://predly.ai/?utm_source=predictefy) - Prediction market analytics platform scanning Polymarket and Kalshi to identify contract mispricings against model-estimated probabilities.
- [Semantic 42](https://42.semanticlayer.io?utm_source=predictefy) - Autonomous trading framework executing verified Polymarket transactions directly from the Base network via the x402 protocol.
- [Simmer](https://simmer.markets?utm_source=predictefy) - Open-source agent harness and SDK for autonomous Polymarket and Kalshi trading with paper trading and modular strategy skills.
- [TatorTrader](https://tatortrader.quickintel.io/?utm_source=predictefy) - Conversational trading interface for placing prediction market bets across Polymarket, Myriad, and Limitless within messaging apps and social timelines.
- [TurbineFi](https://turbinefi.com?utm_source=predictefy) - Algorithmic trading platform for Kalshi and Polymarket to backtest, build, and deploy automated market-making and arbitrage bots.
- [UnifAI](https://unifai.network?utm_source=predictefy) - DeFi infrastructure platform enabling autonomous agents to discover, automate, and optimize liquidity and yield strategies across protocols.

## Aggregators

- [Firefly](https://firefly.social?utm_source=predictefy) - Mobile and web application combining social media feeds, on-chain portfolio tracking, and prediction market betting across multiple networks.
- [Kairos](https://kairos.trade/?utm_source=predictefy) - Cross-venue trading terminal and unified REST and WebSocket API merging Kalshi, Polymarket, and Predict.fun order books with NBBO smart routing.
- [Matchr](https://matchr.xyz?utm_source=predictefy) - Cross-venue aggregator searching markets across Polymarket and Kalshi to route trades to the best available prices and automated yield strategies.
- [OkayBet](https://www.okaybet.app/?utm_source=predictefy) - Prediction market aggregation layer supporting cross-platform parlay betting, automated trading agents, and market discovery.
- [Predictefy](https://predictefy.com/en/markets?utm_source=predictefy) - Aggregates markets, prices, order books, and trades from nine venues into one interface, with cross-venue market matching and compare views.
- [trade.fun](https://trade.fun/?utm_source=predictefy) - Multi-asset trading interface combining Polymarket prediction contracts, Solana spot tokens, and leveraged perpetuals with MEV protection.
- [TradeFox](https://thetradefox.com?utm_source=predictefy) - Prediction market aggregator offering self-custodial order execution, cross-platform liquidity routing, and portfolio management tools.

## Alerts

- [alerts chat](https://alerts.chat/?utm_source=predictefy) - Telegram bot providing configurable real-time price action, odds movement, and volume change notifications for Polymarket and Kalshi.
- [BBB](https://docs.bbb.community?utm_source=predictefy) - Token-gated research community and private terminal delivering on-chain intelligence alerts, custom order execution, and analytics for Polymarket traders.
- [ElonTweets Live](https://elontweets.live/?utm_source=predictefy) - Real-time social monitor tracking Elon Musk's posting frequency and intervals with instant Telegram alerts for prediction market traders.
- [Nevua Markets](https://nevua.markets/?utm_source=predictefy) - Customizable watchlist monitor delivering real-time Polymarket price and volume alerts through Telegram, Discord, webhooks, and browser notifications.
- [PolyAlertHub](https://polyalerthub.com/?utm_source=predictefy) - Notification service dispatching email and Telegram alerts for Polymarket whale transactions, top trader positions, and emerging market trends.
- [PolyCopy](https://polycopy.app?utm_source=predictefy) - Telegram bot tracking Polymarket trader wallets, open positions, and historical performance metrics without requiring private key or wallet connections.
- [PolyIntel](https://t.me/PolyIntel_bot?utm_source=predictefy) - Telegram bot monitoring Polymarket order flow every 10 minutes to detect whale transactions, suspicious trades, and probability shifts.
- [PolySpy](https://t.me/PolySpy_bot?utm_source=predictefy) - Telegram bot delivering instant notifications for newly created Polymarket contracts with granular filtering by topic, category, and custom tag exclusions.
- [Stand](https://www.stand.trade/?utm_source=predictefy) - Wallet monitoring and copy trading tool providing real-time alerts when top Polymarket traders execute high-conviction positions.
- [YN Signals](https://t.me/YNSignals?utm_source=predictefy) - Telegram channel streaming continuous alerts for new market listings, odds anomalies, whale transactions, and active wallet movements across Polymarket, Kalshi, and Limitless.

## Analytics

- [Betmoar](https://www.betmoar.fun/?utm_source=predictefy) - Web trading terminal for Polymarket featuring contract search filters, live news aggregation, and market liquidity metrics.
- [EventWaves](https://www.eventwaves.io/?utm_source=predictefy) - Edge discovery tool for Polymarket evaluating trader skill metrics, price momentum, and volume imbalances.
- [FirePolymarket](https://firepolymarket.com?utm_source=predictefy) - Market scanner classifying Polymarket traders into smart money and whale tiers while scoring contract momentum using Fire Scores.
- [Hashdive](https://www.hashdive.com/?utm_source=predictefy) - Cross-platform dashboard providing trader rankings and contract analytics across Polymarket and Kalshi using proprietary Smart Scores.
- [Markium](https://markiumpro.com/?utm_source=predictefy) - Multi-market aggregator delivering cross-venue trader leaderboards, wallet analytics, and watchlist alerts for Polymarket and peer exchanges.
- [Mention Markets](https://mentionmarkets.com/?utm_source=predictefy) - Transcript search engine indexing political speeches, corporate earnings calls, and Federal Reserve statements for word-count betting contracts.
- [MentionMetrix](https://www.mentionmetrix.com/?utm_source=predictefy) - Keyword analytics service providing historical mention frequencies, speech excerpts, and trend charts for Kalshi and Polymarket contracts.
- [MobyScreener](https://www.mobyscreener.com/predictions-feed?utm_source=predictefy) - Live transaction feed streaming real-time buy and sell orders from top-performing Polymarket traders.
- [Parsec](https://parsec.fi/polymarket?utm_source=predictefy) - Financial data terminal offering real-time charting, order flow visualization, and volume metrics for Polymarket contracts.
- [PM Wisdom](https://pmwisdom.com/?utm_source=predictefy) - Community directory and comparison resource indexing hundreds of prediction market exchanges, data tools, and ecosystem projects.
- [PolyInsider](https://polyinsider.io?utm_source=predictefy) - Real-time dashboard flagging first-time Polymarket wallets placing bets of at least 5,000 dollars, paired with whale trader rankings.
- [Polymarket Analytics](https://polymarketanalytics.com/?utm_source=predictefy) - Web dashboard tracking Polymarket trader leaderboards, open positions, market activity, and aggregate trade volume.
- [Polymarket Elon Tracker](https://t.me/polymarketbetbot?utm_source=predictefy) - Telegram bot tracking Elon Musk tweet frequencies, live orderbook depth, and outcome probabilities for tweet-count betting markets on Polymarket.
- [PolymarketDash](https://www.polymarketdash.com/?utm_source=predictefy) - Trader analytics platform for Polymarket focusing on smart money flow tracking, wallet profiling, and historical market metrics.
- [PolyScope](https://discord.com/invite/polyscope?utm_source=predictefy) - Discord monitoring bot delivering real-time alerts for trending Polymarket contracts, odds shifts, and top trader activity.
- [Polysights](https://app.polysights.xyz/?utm_source=predictefy) - Market analytics dashboard combining custom Polymarket metrics, automated news summaries, and price change alerts.
- [Polysimplr](https://www.polysimplr.com/?utm_source=predictefy) - Conversational web interface featuring an AI assistant to query Polymarket contract details, odds history, and market probabilities.
- [PolyTrack](https://polytrack.cash/?utm_source=predictefy) - Surveillance service monitoring Polymarket for newly funded whale wallets, abnormal trade sizes, and suspicious activity severity scores.
- [PolyVision](https://polyvisionx.com?utm_source=predictefy) - Wallet analyzer calculating copy-trading ratings, Sharpe ratios, and drawdown risks, delivered via Telegram bot, REST API, and MCP server.
- [PolyWallet](https://polywallet.info/?utm_source=predictefy) - Watchlist monitoring tool supporting tracking of up to twenty Polymarket addresses with Telegram alerts and profit leaderboards.
- [PredictFolio](https://predictfolio.com?utm_source=predictefy) - Portfolio tracker for Polymarket enabling users to monitor historical profit and loss, win rates, and comparative trader performance.
- [Predicting Top](https://predicting.top/?utm_source=predictefy) - Leaderboard platform displaying daily profit and loss, win rates, and on-chain wallet addresses for top Polymarket traders.
- [Predicts.guru](https://www.predicts.guru/?utm_source=predictefy) - Wallet analysis platform visualizing Polymarket trade histories, risk-return profiles, win probability distributions, and cumulative profit timelines.
- [Prediedge](https://prediedge.com?utm_source=predictefy) - Whale tracking platform detecting large orders, unusual wallet activity, and volume anomalies across Polymarket and Kalshi.
- [PredScan](https://predscan.io?utm_source=predictefy) - Performance tracking service publishing daily updated Polymarket trader rankings, return on investment figures, and historical win rates.
- [Pricediction](https://web3-pricediction.vercel.app/?utm_source=predictefy) - Research and execution toolkit providing automated market analysis and direct trade execution on Kalshi and Polymarket.
- [Synthesis](https://synthesis.trade/?utm_source=predictefy) - Multi-venue dashboard displaying live orderbooks, bid-ask depth, and cross-market price comparisons across Polymarket, Kalshi, and Limitless.
- [Wethr](https://wethr.net/?utm_source=predictefy) - Meteorological data platform providing live forecast models and temperature tracking for weather markets on Polymarket and Kalshi.
- [Wincy Polymarket Bot](https://t.me/wincy_polymarket_bot?utm_source=predictefy) - Telegram bot detailing the five largest position holders in any Polymarket contract, showing position sizes, directions, and wallet links.

## APIs

- [Adanos Market Sentiment API](https://api.adanos.org/docs/?utm_source=predictefy) - REST API delivering Polymarket sentiment metrics for stocks and ETFs, including buzz scores, directional trend signals, and comparative endpoints for trading tools.
- [Adjacent](https://adjacent.markets/?utm_source=predictefy) - Prediction market indices plus a developer API, pairing real-time news feeds with live market probability data.
- [ClickHouse](https://crypto.clickhouse.com/?utm_source=predictefy) - Open-source columnar OLAP database optimized for real-time analytical queries over high-volume market trades, order book snapshots, and on-chain event logs.
- [Dome](https://domeapi.io?utm_source=predictefy) - Developer platform offering unified REST APIs and SDKs for querying real-time order books and historical trade data across multiple prediction markets.
- [Marketlens](https://marketlens.trade/?utm_source=predictefy) - Quantitative research platform providing tick-level historical Polymarket order book and trade data through a Python SDK and backtesting REST API.
- [PMXT](https://github.com/qoery-com/pmxt?utm_source=predictefy) - Open-source unified API client for querying prediction market data and trading across multiple exchanges through a CCXT-inspired standardized interface.
- [PolyRouter](https://polyrouter.io?utm_source=predictefy) - Unified API service delivering normalized market data from Kalshi, Polymarket, and Limitless through a single API key and standardized interface.
- [Predictefy API](https://www.npmjs.com/package/@predictefy/sdk?utm_source=predictefy) - Normalized REST, WebSocket, and SQL contract with TypeScript and Python SDKs, where reaching another venue means changing the venue parameter.
- [pykalshi](https://github.com/ArshKA/kalshi-client?utm_source=predictefy) - Python client for Kalshi featuring WebSocket streaming, automatic retries, rate limiting, Pandas integration, Jupyter notebook rendering, and local order book management.

## Arbitrage

- [ArbBets](https://getarbitragebets.com/?utm_source=predictefy) - Scanning platform calculating cross-venue arbitrage and positive expected value opportunities across Polymarket, Kalshi, and traditional sportsbooks.
- [Eventarb](https://www.eventarb.com/?utm_source=predictefy) - Free web tool calculating price discrepancies and alerting cross-platform arbitrage opportunities across Polymarket, Kalshi, and Robinhood.
- [Polymarket JB Bot](https://t.me/polymarket_jb_bot?utm_source=predictefy) - Open-source Telegram bot providing automated Polymarket arbitrage alerts, order book depth inspection, and market expiration scanning.
- [PolyScalping](https://polyscalping.org/?utm_source=predictefy) - Market scanner monitoring Polymarket every 60 seconds to detect arbitrage and scalping opportunities with spread filtering, ROI calculations, and Telegram alerts.
- [Polytrage](http://t.me/polytrage?utm_source=predictefy) - Telegram channel posting Polymarket arbitrage signals every 15 minutes with bid-ask spreads and direct trade links.
- [Predictefy Arbitrage](https://predictefy.com/en/arbitrage?utm_source=predictefy) - Cross-venue price discrepancies between matched markets, labeled indicative or executable depending on whether live book and execution gates pass.
- [Prediction Hunt](https://predictionhunt.com/?utm_source=predictefy) - Cross-exchange comparison platform updating every five minutes to detect arbitrage opportunities and match equivalent contracts across Kalshi, Polymarket, and PredictIt.

## Dashboards

- [DefiLlama](https://defillama.com/?utm_source=predictefy) - Open data aggregator tracking total value locked, trading volumes, protocol revenue, and token fees across blockchains and prediction protocols.
- [fergmolina](https://dune.com/fergmolina/polymarket-markets-data?utm_source=predictefy) - Dune Analytics dashboard visualizing Polymarket on-chain transaction data, open event contracts, and active user metrics via Gamma API integration.
- [KuCoinVentures](https://dune.com/kucoinventures/trading-bots-on-polymarket?utm_source=predictefy) - Dune Analytics dashboard tracking automated trading bot activity, transaction volume share, and address behavior across Polymarket order books.
- [LayerHub](https://layerhub.xyz/protocols/polymarket?utm_source=predictefy) - On-chain analytics dashboard tracking Polymarket wallet interaction history, volume distributions, user retention metrics, and individual trader performance.
- [Pizzint Watch](https://www.pizzint.watch/?utm_source=predictefy) - Dashboard correlating late-night pizza shop foot traffic near the Pentagon with Polymarket geopolitical contract pricing for OSINT signals.
- [Token Terminal](https://tokenterminal.com?utm_source=predictefy) - Financial analytics platform standardizing on-chain metrics, protocol revenue, active users, and fee data for blockchains and decentralized applications.
- [Zapper](https://zapper.xyz/apps/polymarket?utm_source=predictefy) - Web3 portfolio dashboard featuring integrated Polymarket position tracking, multi-chain balance monitoring, and on-chain transaction history across EVM networks.

## Data

- [alexmccullough](https://dune.com/alexmccullough/how-accurate-is-polymarket?utm_source=predictefy#a-few-things-immediately-stand-out) - Dune Analytics dashboard analyzing Polymarket historical contract calibration, outcome distributions, probability biases, and accuracy across price buckets.
- [Artemis](https://www.artemis.ai/sectors?tab=prediction_markets&utm_source=predictefy) - Market data platform tracking real-time trading volume, open interest, daily active users, and transaction flows across Polymarket and Kalshi.
- [Blockworks](https://blockworks.com/analytics/polymarket?utm_source=predictefy) - Research analytics suite tracking Polymarket on-chain activity, daily volume breakdowns, liquidity distribution, and active wallet segments.
- [filarm](https://dune.com/filarm/polymarket-activity?utm_source=predictefy) - Dune Analytics dashboard tracking Polymarket daily active traders, cumulative volume trends, token liquidity, and monthly user growth metrics.
- [Goldsky](https://goldsky.com/?utm_source=predictefy) - Data indexing infrastructure providing real-time subgraphs, custom data pipelines, and webhook streaming for Polymarket on-chain events.
- [Probalytics](https://probalytics.io?utm_source=predictefy) - Data infrastructure for Polymarket and Kalshi with REST APIs, ClickHouse SQL access, 1ms resolution order book updates, and Parquet S3 bulk exports.
- [sealaunch](https://dune.com/sealaunch/polymarket-trending-topics?utm_source=predictefy) - Dune Analytics dashboard tracking trending Polymarket topics, 24-hour volume spikes, open interest, and probability shifts across breaking event contracts.
- [TREMOR](https://github.com/sculptdotfun/tremor?utm_source=predictefy) - Data terminal for Polymarket and Kalshi offering SQL query analytics, sub-second latency, and market intelligence across active event contracts.

## DeFi

- [Aura](https://aura.money/?utm_source=predictefy) - Combining sports, politics, crypto perpetuals, and real-world-asset perpetuals into one trading venue backed by Polymarket and Hyperliquid liquidity.
- [Gondor](https://gondor.fi/?utm_source=predictefy) - Lending protocol letting traders borrow against open Polymarket positions, freeing up liquidity without forcing them to close trades.
- [HyperOdd](https://hyperodd.com?utm_source=predictefy) - Leveraged trading platform for prediction markets, offering up to 20x leverage across politics, sports, crypto, and stock outcomes.
- [Ostium](https://app.ostium.com/strategies?utm_source=predictefy) - Automating trading strategy execution on top of Polymarket market data for hands-free, rule-based position management.
- [Robin](https://robin.markets?utm_source=predictefy) - Yield-focused platform that deploys capital into delta-neutral strategies to earn DeFi yield on top of Polymarket positions automatically.
- [SuiBets](https://suibets.com/?utm_source=predictefy) - Decentralized sports betting protocol on the Sui network, settling wagers on-chain with a multisig treasury and formally verified smart contracts.

## Education

- [PolymarketGuide](https://polymarketguide.gitbook.io/?utm_source=predictefy) - Independent knowledge base explaining how Polymarket resolves markets, with precedent examples and case studies for traders and oracle participants.
- [PolyNoob](https://polynoob.com/?utm_source=predictefy) - Beginner-focused encyclopedia and guide covering Polymarket trading strategies, trader insights, and other educational material for new users.
- [The Oracle by Polymarket](https://news.polymarket.com/?utm_source=predictefy) - Newsletter and podcast produced by Polymarket, covering news, market commentary, and analysis tied to live prediction market activity.
- [Hyperliquid Academy](https://hyperliquidacademy.com/compare/hyperliquid-vs-polymarket/) - Independent comparison of Polymarket and Hyperliquid HIP-4 outcome markets on settlement, fees and access, dated and sourced.

## Extensions

- [PMs4X](https://chromewebstore.google.com/detail/prediction-markets-for-x/cpimmfoflnoomfabkemagplkjeaemndp?utm_source=predictefy) - Chrome browser extension that surfaces matching Polymarket markets directly inside Twitter/X timelines, with no signup, wallet connection, or data collection required.

## Funds

- [PolyFund](https://www.polyfund.so/?utm_source=predictefy) - Decentralized platform connecting skilled Polymarket traders who manage pooled funds with investors seeking exposure to their trading expertise.

## Infrastructure

- [Baozi.bet](https://baozi.bet?utm_source=predictefy) - Decentralized pari-mutuel prediction market protocol on Solana, offering boolean and multi-outcome race markets plus an open-source MCP server for AI agent integration.
- [Compose](https://compose.build?utm_source=predictefy) - Orchestration framework connecting offchain and onchain systems, helping developers build hybrid onchain applications in TypeScript with automated workflow management.
- [Dimes](https://dimes.fi?utm_source=predictefy) - Embedded credit infrastructure letting trading terminals, wallets, and apps offer leveraged prediction market exposure through a REST API, handling credit provisioning and hedging.
- [Kuest](https://kuest.com?utm_source=predictefy) - Open-source infrastructure protocol that lets developers launch and operate their own prediction market deployment on the Polygon network.
- [OrderbookTrade](https://www.orderbook.trade?utm_source=predictefy) - CLOB-based matching engine and on-chain settlement infrastructure that lets operators launch a prediction market venue with one click.
- [SEDA](https://docs.seda.xyz/?utm_source=predictefy) - Oracle infrastructure bringing Polymarket market data onchain, letting developers build composable DeFi primitives such as perpetuals, lending, and arbitrage tools across chains.

## News

- [Boring News](https://www.notboring.co/?utm_source=predictefy) - Daily news show built around Polymarket odds as its data foundation, publishing episodes across YouTube, X, and podcast platforms.
- [DeepNewz](https://deepnewz.com/?utm_source=predictefy) - News app that personalizes story feeds and attaches live prediction market odds to each headline using AI-driven curation.
- [Prediction News](https://predictionnews.com/?utm_source=predictefy) - News site publishing articles, analysis, and data-driven insights that track the prediction market industry across platforms and events.
- [PROPHET](https://www.prophetnotes.com/?utm_source=predictefy) - Newsletter delivering forecasting insights on politics, finance, and geopolitics, drawing on input from outside subject-matter experts.
- [Stocktwits](https://stocktwits.com?utm_source=predictefy) - Social platform for traders and investors that layers prediction market probabilities on top of real-time market discussion feeds.

## Official

- [Polymarket Live Ticker](https://ticker.polymarket.com?utm_source=predictefy) - Official widget service from Polymarket that streams live market data feeds into livestreams, websites, and mobile apps, with direct OBS integration.

## Parlays

- [BetStack](https://alpha.betstack.app?utm_source=predictefy) - Sports betting app built on Polymarket that lets users chain multiple prediction market bets into sequential parlays with live cashout.
- [Clutch](http://ape.clutch.market?utm_source=predictefy) - On-chain parlay platform combining Polymarket, sports, and political predictions into single higher-payout bets, running on Arbitrum and ApeChain.
- [PredictShark](https://www.predictshark.io/?utm_source=predictefy) - Polygon-based parlay platform letting users combine multiple Polymarket events into a single on-chain bet, settled trustlessly using native USDC.

## Portfolio Tracking

- [Polycool](https://polycool.live/?utm_source=predictefy) - Trader tracking platform flagging large trades from Polymarket's busiest half percent of wallets, delivered as Telegram alerts with copy trading options.
- [Polylerts](https://t.me/Polylerts_bot?utm_source=predictefy) - Free Telegram bot tracking up to 15 Polymarket wallets at once, sending trade alerts and analytical reports to study top traders.
- [PolyTracker](https://t.me/polytracker0_bot?utm_source=predictefy) - Telegram bot that watches chosen Polymarket wallets and sends notifications on new transactions with market details and direct links.

## Trading Bots

- [AIXBET](https://www.aixbet.ai/?utm_source=predictefy) - Autonomous betting protocol that executes trades on Polymarket and similar markets around the clock, using AI models and smart money signals.
- [Based](https://app.based.one/predict?utm_source=predictefy) - Unified Hyperliquid trading platform that folds Polymarket prediction markets into the same account as perpetuals, spot crypto, and on-chain stock trading.
- [Berry](https://berry.app/?utm_source=predictefy) - Mobile investing app offering US stocks, ETFs, and Polymarket-powered prediction markets in one account, with no bank account required to start.
- [Converge](https://converge.market?utm_source=predictefy) - Trading terminal aggregating Polymarket, Kalshi, and Limitless into one custody-free, chain-agnostic interface with cross-venue arbitrage detection and no added fees.
- [Datalayer](https://datalayer.xyz/?utm_source=predictefy) - AI trading companion spanning meme coins, perpetuals, yield farming, and prediction markets across Hyperliquid, Polymarket, Solana, BSC, and Base.
- [Fireplace](https://fireplace.gg/?utm_source=predictefy) - Social news feed app built on Polymarket, letting friends scroll headlines, place bets on breaking news markets, and compete on leaderboards.
- [okbet](https://tryokbet.com/?utm_source=predictefy) - Telegram terminal covering both Polymarket and Kalshi, letting groups of friends trade, place bets, and copy top performers from chat.
- [PolyBot](https://polybot.trading/?utm_source=predictefy) - Self-custodial Telegram trading bot for Polymarket using Gnosis Safe wallets, with gas-sponsored transactions and paste-to-trade execution inside chat.
- [Polyburg](https://polyburg.com/?utm_source=predictefy) - Intelligence terminal tracking Polymarket's most profitable wallets through automated monitoring, AI-generated insights, and instant Telegram alerts.
- [Polycule](https://www.polycule.trade/?utm_source=predictefy) - Telegram bot for trading Polymarket markets from mobile chats, supporting solo, social, and group trade execution.
- [PolyFocus](https://t.me/polyfocusbot?utm_source=predictefy) - Telegram trading bot for Polymarket combining copy trading, multi-chain wallet management, and tools for discovering new markets.
- [Polylayer](https://polylayer.xyz?utm_source=predictefy) - Layer 2 prediction finance ecosystem built on Polymarket, combining leveraged trading, yield generation, automated strategies, and derivatives infrastructure in one stack.
- [Polymtrade](https://polym.trade/?utm_source=predictefy) - Mobile trading terminal for Polymarket markets, pairing order execution with AI-generated market insights on a phone-first interface.
- [PolyScope Bot](https://polyscope.gitbook.io?utm_source=predictefy) - Wallet tracking and analytics bot using AI models to profile traders and send alerts across Polymarket and other prediction platforms.
- [PolyXBot](https://www.polyxbot.org/?utm_source=predictefy) - Solana-native Telegram bot for Polymarket trading that bundles AI market analysis, cross-chain bridging, and portfolio management into one chat interface.
- [Predictify](https://t.me/Predictify_bot?utm_source=predictefy) - Telegram-based, fully on-chain aggregator spanning Polymarket and Solana-native prediction markets, with trade execution, copy trading, and analytics on mobile.
- [Predicton](https://predicton-guide.gitbook.io?utm_source=predictefy) - TON-native Telegram bot for trading politics, news, and sports predictions, drawing market data and liquidity from Polymarket.
- [Rainmaker](https://rainmaker.fun/?utm_source=predictefy) - AI agent terminal unifying arbitrage scanning, copy trading, and analytics across Polymarket and Kalshi, branded as the Cloud9 Agentic Terminal.
- [Rocket](https://userocket.app/?utm_source=predictefy) - Prediction market aggregator that pulls odds and forecasts into one dashboard for cross-market analysis and comparison.
- [Sharpe Terminal](https://beta.sharpeterminal.com/?utm_source=predictefy) - Trading terminal for prediction markets offering order management, market monitoring, and Polymarket social feeds with trader analytics, currently in public beta.

## Other

- [Cookie fun](https://www.cookie.fun/tokens/polymarket?utm_source=predictefy) - Index and data layer for AI agent tokens, ranking top gainers by mindshare, follower quality, engagement, and onchain activity.
- [Dexu](https://dexu.ai/project/polymarket?id=2037&utm_source=predictefy) - Analytics platform using AI models to detect emerging trends and quantify social attention across prediction markets and crypto narratives.
- [Kaito](https://kaito.ai/?utm_source=predictefy) - Web3 analytics platform tracking mindshare and social attention across prediction market projects, with creator leaderboards and engagement rankings.
- [Liquid](https://protocol.useliquid.xyz?utm_source=predictefy) - Insurance protocol for prediction market bets, letting traders set loss caps and activate cash-back protection with a single tap.
- [PolyFakeIt](https://www.polyfakeit.com/?utm_source=predictefy) - Mockup generator producing fake prediction market screenshots with customizable odds, charts, and betting interfaces for entertainment and content creation.
- [PolyHedg](https://polyhedg.com/?utm_source=predictefy) - Platform that converts corporate event risk into a fixed, budgetable cost using automated hedging strategies built on Polymarket markets.
- [Polyteller](https://polyteller.com/?utm_source=predictefy) - Free Chrome extension adding live market countdowns, trade notifications, a privacy mode, and safety checks for Polymarket traders.
- [Prediction Index](https://predictionindex.xyz/?utm_source=predictefy) - Ranking dashboard and directory listing over 140 prediction market projects, filterable by chain, market type, and operating status.
- [UMA rocks](https://www.uma.rocks/?utm_source=predictefy) - Self-custodial platform automating UMA token delegation for oracle voting rewards tied to Polymarket dispute resolution.
