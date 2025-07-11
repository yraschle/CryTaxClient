## CryTax Client

**Cryptocurrency Tax Calculator**

CryTax is a report generator for tax-related calculations for cryptocurrencies and other assets. It tracks transactions over the ledger and calculates tax-related gains and losses. Currently, the application only accepts ledger files structured in the Kraken standard ledger format.
The application is written primarily in Python and uses FastAPI to serve reports to a simple Vue.js frontend.

**Built with:** 
- Frontend: Vue.js  
- Backend: Python with FastAPI
- PDF generator: FPDF
- Status: In Progress

**Some features:** 
- Transaction backtracking and analysis
- Gain/loss calculation
- Report generation

[Live Project](https://yraschle.github.io/CryTaxClient)
