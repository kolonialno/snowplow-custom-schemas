# Snowplow custom schemas 

Public repo for custom Snowplow schemas used by Fivetran.

Fivetrans requirements does not comply with the Iglu specification. See the current schemas for inspiration to create new ones. Some hard requirements are:
- `title` must be inclued (this will become the table name in Snowflake)
- Only homogeneous arrays are supported (i.e only "integer" f.ex)

For more information about json schema definitions and how they can be used in Snowplow, have a look [here](https://docs.snowplowanalytics.com/docs/understanding-tracking-design/predefined-vs-custom-entities/).

## Deploying 

Deploying is simply done by commiting to main branch.
