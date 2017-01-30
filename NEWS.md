### Version 1.2.4 (2017-01-30)

Minor update:

* Fixed bug in msg output when length(my.assets) > 2

### Version 1.2.3 (2017-01-13)

Minor update:

* Fixed bug for non existing assets in first date of download process
* Changed input Date for simpler format (e.g. '2016-01-01' and not as.Date('2016-01-01'))

### Version 1.2.2 (2016-12-05)

Minor update:

* Revised apa citation on attach
* Fixed some typos in vignette and added link to SSRN paper

### Version 1.2.1 (2016-11-07)

Minor update with the following changes:

* The user can now download data from the odd lots equity market (type.market='equity-odds')
* Added Henrique Ramos as a contributor
* Other minor changes

### Version 1.2.0 (2016-10-14)

Minor update with the following changes:

* The function  ghfd_get_HF_data now allows for partial matching of asset names and also the download of all assets available in ftp files
* Function ghfd_get_available_tickers_from_ftp also returns the type of market in data.frame 

### Version 1.1.0 (2016-08-15)

Major update from initial version with the following changes:

* The function for finding tickers in the ftp now looks for the closest date in the case that the actual date is missing from the ftp
* The function for finding tickers now returns a dataframe with the tickers and number of trades
* Added control for bad files
* The output for raw and agg type of output were revised
* The vignette is revised

### Version 1.0.0 - First commit (2016-07-21)