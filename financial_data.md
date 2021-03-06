# Financial data
- Knowledge graphs/Ontologies
  - https://permid.org/, easy match to Reuters RICs
  - https://www.openfigi.com/, easy match to Bloomberg IDs
    - Bloomberg open symbology as RDF: [source code](https://github.com/ga-group/bsym), [data](https://old.datahub.io/dataset/figi)
  - [Financial Industry Business Ontology](https://spec.edmcouncil.org/fibo/)
  - [GA-group (BSYM project)](https://github.com/ga-group/bsym)
  - [The Fund Ontology](http://fundontology.com/)
- Market identifiers (and matchings)
  - [MIC (ISO 10383)](https://www.iso20022.org/10383/iso-10383-market-identifier-codes)
  - Proprietary codes
    - [Bloomberg Exchange Code to MIC mapping](https://openfigi.com/assets/local/exchange-code-mic-mapping.xls)
    - [Yahoo market identifiers & data providers](https://help.yahoo.com/kb/SLN2310.html)
- Instrument identifiers
  - [ANNA ISIN (ISO 6166) lookup service](http://www.anna-web.org/anna-launches-free-international-isin-lookup-service/)
  - [CFI: Classification of Financial Instruments (ISO 10962)](http://www.anna-web.org/standards/cfi-iso-10962/)
  - [FISN: Financial Instrument Short Name (ISO 18774)](http://www.anna-web.org/standards/fisn-iso-18774/)
  - Proprietary codes (and matchings)
    - [CBOE Europe](http://cdn.batstrading.com/resources/participant_resources/BATS_Europe_Reference_Data.pdf) (sometimes includes mapping to Reuters RIC codes and Bloomberg tickers)
    - [STOXX indices](https://www.stoxx.com/data-vendor-codes), ISIN, Proprietary, Bloomberg, Reuters, disemmination time
    - [S&P DJ indices](http://www.spice-indices.com/idpfiles/spice-assets/resources/public/documents/spdji-tickers-etf.pdf), Bloomberg, Reuters
    - [MSCI indices](https://www.msci.com/ticker-codes), Bloomberg, Reuters
    - [All Yahoo symbol identifiers](http://investexcel.net/all-yahoo-finance-stock-tickers/) in an Excel spreadsheet
    - [Eurex](http://www.eurexchange.com/exchange-en/products/vendor-product-codes/), Bloomberg, Reuters, etc.
    - [CME settlements](http://www.cmegroup.com/market-data/settlements.html), CME codes
    - [CME](http://www.cmegroup.com/tools-information/vendorSymbol.html), Bloomberg, Reuters, CQG, etc.

- Company/legal entity identifiers
  -  [Global Legal Entity Identifier (LEI) (ISO 17442)](https://www.gleif.org/en/about-lei/iso-17442-the-lei-code-structure)
- Symbologies:
  - [Reuters RICs](http://findb.aalto.fi/docs/Reuters/reuters_dataguide.pdf)
  - [Bloomberg Open Symbology](https://openfigi.com/about)
- Identifier validators
  - [identifiers Python package](https://pypi.python.org/pypi/identifiers/0.3.1)
- APIs
  - Free
    - [Alpha Vantage](https://www.alphavantage.co/documentation/), stocks, forex, cryptocurrencies, technical indicators, sector info
    - [IEX](https://iextrading.com/developer/docs/), stocks
    - [Cryptowat.ch](https://cryptowat.ch/docs/api), cryptocurrencies
- Financial instrument data
  - Funds
    - [MorningStar Funds](https://www.morningstar.com/funds.html)
    - [FundsSquare](https://www.fundsquare.net/homepage)
    - [FundsDLT](https://www.fundsdlt.net/)
    - [FundsLibrary.co.uk](https://www.fundslibrary.co.uk/FundsLibrary.DataApi.Web/)
    - [FundInfo Datahub](https://datahub.fundinfo.com/)
  - Stocks
    - [Yahoo finance screener](https://finance.yahoo.com/screener)
  - Anything
    - [Financial Times Markets](https://markets.ft.com/data/search)
    - [Interactive Brokers](https://misc.interactivebrokers.com/cstools/contract_info/)
- Calendars & events
  - [Thomson Reuters Economic Data](https://financial.thomsonreuters.com/en/products/data-analytics/economic-data.html), paid service
  - [Yahoo Finance Events Calendar](https://finance.yahoo.com/calendar), earnings, splits, IPOs, data releases
  - [Interactive Brokers Calendar](https://www.interactivebrokers.com/calendar/), international holidays & expirations
  - [fxstreet economic calendar](https://www.fxstreet.com/economic-calendar)
  - [global-rates.com](http://www.global-rates.com/), up-to-date global interest rates
