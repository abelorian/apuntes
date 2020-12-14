
elastic search 

{"type"=>"cluster_block_exception", "reason"=>"blocked by: [FORBIDDEN/12/index read-only / allow delete (api)];"}


curl -XPUT -H "Content-Type: application/json" http://localhost:9200/_all/_settings -d '{"index.blocks.read_only_allow_delete": null}'

condigurar UFW con IP 0.0.0.0


elasticsearch-plugin install x-pack

sudo service elasticsearch restart

sudo service elasticsearch status

curl -X POST -u elastic:changeme 'localhost:9200/_xpack/security/user/elastic/_password?pretty' -H 'Content-Type: application/json' -d '{ "password" : "secret"}'


