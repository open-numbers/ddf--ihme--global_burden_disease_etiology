# Global Burden of Disease from IHME

IHME GBD etiology by cause and risk

Source: [GBD 2016](http://ghdx.healthdata.org/gbd-2016). The source
files are downloaded from [GBD result tool](http://ghdx.healthdata.org/gbd-results-tool)

# Indicators in this dataset

Below measures are available for the context "etiology" in GBD:

- deaths
- dalys
- ylls
- ylds

And each measure is available in 3 units:

- Number
- Rate per 100K people
- Percent

We have combined these measures and metrics, and created following
indicators in this dataset:

- deaths_number
- deaths_percent
- deaths_rate
- ylls_number
- ylls_percent
- ylls_rate
- ylds_number
- ylds_percent
- ylds_rate
- dalys_number
- dalys_percent
- dalys_rate

## Notes

1. uncertainty level upper bound and lower bound values are not
   included in the dataset. Only median values are included.
2. at most 2 decimal digits are kept for numbers.
3. only country level data available; city/state/region/world level
   data are not in the dataset
4. only aggregated age groups "all age" and "age standardized" are
   available
