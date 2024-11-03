# TukDB &mdash; Search Database

**Search instantly. Scale effortlessly.**


## What is TukDB?

TukDB is a search database designed to intelligently handle high-performance search tasks on large-scale datasets while needing only a fraction of the hardware required by traditional search engines. Our mission is to provide a robust solution that empowers developers to implement efficient search functionalities across various applications.


For more information, please check out [TukDB website](https://tukdb.com).


## Where's the code?

We're working hard to ensure TukDB's core features meet the stability and performance standards we believe are essential. As soon as these are fully realized, we’ll release the initial version of TukDB as open-source software.



## What core features?

 - **Get started in seconds** - Single node instance is trivially easy to set up. New users and developers are not expected to provide numerous configuration parameters or complicated config files.
  - **Scale easily** - Data distribution is handled automatically. Adding new data volumes or servers to the cluster is a simple config change away.
 - **Adaptable to diverse hardware** - TukDB cluster takes full advantage of all hardware given to it, regardless of performance characteristics of each server. It automatically rebalances in order to minimize tail latencies for critical query patterns.
 - **Highly available - in a fraction of disk space** - TukDB uses distributed LSM trees that provide quorum-like consistency query model, but implemented so that indexes don't require all replicas to maintain all data, allowing for substantially increased storage capacity.
 - **Self-healing** - As soon as any data volume or server is unhealthy, TukDB cluster automatically sets up additional replicas for affected segments on healthy nodes.
 - **Flexible querying** - TukDB accepts query syntax compatible with Elasticsearch, Opensearch, and Apache Solr. It also comes with its own client-side libraries for common programming languages, allowing a higher level of query optimizations.


## License

This project is licensed under the Functional Source License, Version 1.1, with future Apache License 2.0. Check the LICENSE file for details.
