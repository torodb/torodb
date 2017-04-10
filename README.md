# ToroDB

ToroDB is a technology designed to fulfill the gap between document oriented
and SQL databases. There are two products that use this technology: [ToroDB Server][6] 
and [ToroDB Stampede][7]. Both platforms are open source and any feedback,
contributions, help and/or patches are very welcome. Please join the
[torodb-dev][2] mailing list for further discussion.

For more information, please see [ToroDB's website][1]

## ToroDB Server
It is a MongoDB-compatible server that supports speaks the MongoDB Wire 
Protocol (and therefore can be used with the same drivers used to connect to 
any standard MongoDB server) but stores your data into a reliable and trusted 
ACID database. 

More information about ToroDB Server can be found on [its own repository][6].

## ToroDB Stampede
ToroDB Stampede is a business analytic solution that replicates your data in 
real time from a MongoDB replica set into a SQL database, allowing you to use
any business intelligence products (like [Tableau][3] or [Pentaho][4]) to 
analyze NoSQL data.

As it replicates your MongoDB data, ToroDB Stampede can be used to migrate
from MongoDB to SQL databases.

More information about ToroDB Stampede can be found on 
[its own repository][7] or on the [product website][8]

## Meta

ToroDB – [@nosqlonsql][5] – info@8kdata.com

[1]: http://www.torodb.com
[2]: https://groups.google.com/forum/#!forum/torodb-dev
[3]: http://www.tableau.com
[4]: http://www.pentaho.com/
[5]: https://twitter.com/nosqlonsql
[6]: https://github.com/torodb/server
[7]: https://github.com/torodb/stampede
[8]: http://www.torodb.com/stampede
