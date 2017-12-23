# patentsview 0.2.0 (2018-01-01)

#### New functions

* `cast_pv_data` added to convert the data types of the data returned by 
  `search_pv`
  
#### New fields

* Additional fields added to API (e.g., fields starting with `forprior_`, `examiner_`)

# patentsview 0.1.0 (2017-05-01)

#### New functions

* `search_pv` added to send requests to the PatentsView API
* `qry_funs` list added with functions to help users write queries
* `get_fields` and `get_endpoints` added to quickly get possible field names 
  and endpoints, respectively
* `unnest_pv_data` added to unnest the data frames in the returned data