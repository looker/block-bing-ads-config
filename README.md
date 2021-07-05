# Bing Ads Block Configuration Project

THIS BLOCK IS DEPRECATED AS OF 4/2/2021.

This project consists of configuration files for the Bing Ads block project `block-bing-ads`
If installed through the marketplace, input the schema and connection values in the install workflow, otherwise edit them in the `manifest.lkml` file.

## To install this block manually, you will need to:

1. Update the constants in the `manifest.lkml` to point to your specific bing ads schema and connection name.

2. Enable the Project Import feature currently in /admin/labs on your Looker instance.


Note that the `ref:` should point to the latest commit in the core block repo [block-bing-ads](https://github.com/looker/block-bing-ads/commits/master)

### Block Info

This Block is modeled on the schema from Fivetrans's [Bing Ads ETL](https://fivetran.com/directory/bing-ads).

The schema documentation for Bing Ads can be found in [Bing's docs](https://docs.microsoft.com/en-us/advertising/guides/reference?view=bingads-13).


