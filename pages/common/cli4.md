# cli4

> Command line access to Cloudflare v4 API.
> More information: <PUT A LINK HERE>.

- List information for all zones under profile_name:

`cli4 --profile {{profile_name}} /zones`

- Delete a provided zone:

`cli4 --delete /zones/{{:example.com}}`

- Enable DNSSEC for specific zone:

`cli4 --patch status=active /zones/{{:example.com}}/dnssec`

- Purge cache for a specific zone:

`cli4 --delete purge_everything=true /zones/{{:example.com}}/purge_cache`
