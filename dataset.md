Dataset Export
================

# My Dataset

``` r
library(readxl)

nyd_sta <- read_excel("~/Desktop/nyd-sta.xlsx")
head(nyd_sta)
```

    ## # A tibble: 6 × 34
    ##   PropertyID Price `Property Type` `Listing Type`  Neighborhood
    ##        <dbl> <dbl> <chr>           <chr>           <chr>       
    ## 1       8343   375 Apartment       Entire home/apt East Village
    ## 2       8343   375 Apartment       Entire home/apt East Village
    ## 3       8343   375 Apartment       Entire home/apt East Village
    ## 4       8343   375 Apartment       Entire home/apt East Village
    ## 5       8343   375 Apartment       Entire home/apt East Village
    ## 6       8343   375 Apartment       Entire home/apt East Village
    ## # ℹ 29 more variables: `Average Daily Rate` <dbl>, `Annual Revenue LTM` <dbl>,
    ## #   `Occupancy Rate LTM` <dbl>, `Number of Bookings LTM` <dbl>,
    ## #   `Number of Reviews` <dbl>, `Overall Rating` <dbl>, Bedrooms <dbl>,
    ## #   Bathrooms <dbl>, `Max Guests` <dbl>, `Response Rate` <dbl>,
    ## #   `Response Time (min)` <dbl>, Superhost <chr>, `Cancellation Policy` <chr>,
    ## #   `Security Deposit` <dbl>, `Cleaning Fee` <dbl>, `Extra People Fee` <dbl>,
    ## #   `Published Nightly Rate` <dbl>, `Published Monthly Rate` <dbl>, …

``` r
knitr::kable(head(nyd_sta), format = "markdown")
```

| PropertyID | Price | Property Type | Listing Type    | Neighborhood | Average Daily Rate | Annual Revenue LTM | Occupancy Rate LTM | Number of Bookings LTM | Number of Reviews | Overall Rating | Bedrooms | Bathrooms | Max Guests | Response Rate | Response Time (min) | Superhost | Cancellation Policy | Security Deposit | Cleaning Fee | Extra People Fee | Published Nightly Rate | Published Monthly Rate | Published Weekly Rate | Minimum Stay | Count Reservation Days LTM | Count Available Days LTM | Count Blocked Days LTM | Number of Photos | Business Ready | Instantbook Enabled | Latitude | Longitude |   B |
|-----------:|------:|:--------------|:----------------|:-------------|-------------------:|-------------------:|-------------------:|-----------------------:|------------------:|---------------:|---------:|----------:|-----------:|--------------:|--------------------:|:----------|:--------------------|-----------------:|-------------:|-----------------:|-----------------------:|-----------------------:|----------------------:|-------------:|---------------------------:|-------------------------:|-----------------------:|-----------------:|:---------------|:--------------------|---------:|----------:|----:|
|       8343 |   375 | Apartment     | Entire home/apt | East Village |                405 |               8100 |                0.8 |                      5 |                10 |            4.8 |        3 |       1.5 |          6 |           100 |               93.21 | FALSE     | Strict              |              500 |          120 |               35 |                    495 |                   5500 |                  2200 |            3 |                         20 |                       19 |                    327 |               14 | FALSE          | No                  | 40.72481 | -73.98057 |   1 |
|       8343 |   375 | Apartment     | Entire home/apt | East Village |                405 |               8100 |                0.8 |                      5 |                10 |            4.8 |        3 |       1.5 |          6 |           100 |               93.21 | FALSE     | Strict              |              500 |          120 |               35 |                    495 |                   5500 |                  2200 |            3 |                         20 |                       19 |                    327 |               14 | FALSE          | No                  | 40.72481 | -73.98057 |   1 |
|       8343 |   375 | Apartment     | Entire home/apt | East Village |                405 |               8100 |                0.8 |                      5 |                10 |            4.8 |        3 |       1.5 |          6 |           100 |               93.21 | FALSE     | Strict              |              500 |          120 |               35 |                    495 |                   5500 |                  2200 |            3 |                         20 |                       19 |                    327 |               14 | FALSE          | No                  | 40.72481 | -73.98057 |   0 |
|       8343 |   375 | Apartment     | Entire home/apt | East Village |                405 |               8100 |                0.8 |                      5 |                10 |            4.8 |        3 |       1.5 |          6 |           100 |               93.21 | FALSE     | Strict              |              500 |          120 |               35 |                    495 |                   5500 |                  2200 |            3 |                         20 |                       19 |                    327 |               14 | FALSE          | No                  | 40.72481 | -73.98057 |   0 |
|       8343 |   375 | Apartment     | Entire home/apt | East Village |                405 |               8100 |                0.8 |                      5 |                10 |            4.8 |        3 |       1.5 |          6 |           100 |               93.21 | FALSE     | Strict              |              500 |          120 |               35 |                    495 |                   5500 |                  2200 |            3 |                         20 |                       19 |                    327 |               14 | FALSE          | No                  | 40.72481 | -73.98057 |   0 |
|       8343 |   375 | Apartment     | Entire home/apt | East Village |                405 |               8100 |                0.8 |                      5 |                10 |            4.8 |        3 |       1.5 |          6 |           100 |               93.21 | FALSE     | Strict              |              500 |          120 |               35 |                    495 |                   5500 |                  2200 |            3 |                         20 |                       19 |                    327 |               14 | FALSE          | No                  | 40.72481 | -73.98057 |   1 |
