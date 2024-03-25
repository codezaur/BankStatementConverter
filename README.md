# BankStatementConverter
Converts PDF bank statements into CSV file. Can be useful for those working in accounting or finance, where multiple bank statements can be processed every month, oftentimes processed manually.

Personal project [bank statement converter](https://bankstatementconverter.org/) done with Python (Django) on backend and Javascript (Angular) on frontend.
Done with some SEO optimization on frontend side, both generic like SSR, schema markup, meta tags and Angular specifi like ngSkipHydration or NgOptimizedImage.


Backend part done with few libraries for data processing. It extractes tabled from PDF document (transaction data are generally stored within tables), recognises if table actually has transaction data, and if yes, converts into csv.

Code is not exposed, for reasons I belive are obvious :sweat_smile:
