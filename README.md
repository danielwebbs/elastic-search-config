### Personal setup just for playing around with ES, nothing here should be used

https://www.elastic.co/guide/en/elasticsearch/reference/current/vm-max-map-count.html

`sysctl -w vm.max_map_count=262144`

Can't spin up the clusters without increasing the max allowed virtual memory on linux (as I understand it at time of writing).