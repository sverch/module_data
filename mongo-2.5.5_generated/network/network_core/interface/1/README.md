
# Interface

### src/mongo/util/net/sock.cpp

<div></div>

    mongo::hostbyname(char const*)

- Used By:

    - [src/mongo/s/config.cpp](../../../sharding)
    - [src/mongo/dbtests/socktests.cpp](../../../unit\_tests)

<div></div>

    mongo::Socket::unsafe_recv(char*, int)

- Used By:

    - [src/mongo/util/net/miniwebserver.cpp](../../../web\_server)
    - [src/mongo/util/net/httpclient.cpp](../../../rest\_client)

<div></div>

    typeinfo for mongo::SocketException

- Used By:

    - [src/mongo/util/net/ssl\_manager.cpp](../../../ssl)
    - [src/mongo/client/dbclient.cpp](../../../cpp\_client\_driver)
    - [src/mongo/s/server.cpp](../../../mongos\_and\_mongod\_mains)
    - [src/mongo/client/connpool.cpp](../../../cpp\_client\_driver)
    - [src/mongo/db/repl/rs\_initialsync.cpp](../../../replication)
    - [src/mongo/dbtests/mock/mock\_dbclient\_connection.cpp](../../../unit\_tests)
    - [src/mongo/util/net/miniwebserver.cpp](../../../web\_server)
    - [src/mongo/dbtests/mock/mock\_remote\_db\_server.cpp](../../../unit\_tests)
    - [src/mongo/db/repl/sync.cpp](../../../replication)
    - [src/mongo/client/parallel.cpp](../../../cpp\_client\_driver)
    - [src/mongo/util/net/httpclient.cpp](../../../rest\_client)

<div></div>

    mongo::portRecvFlags

- Used By:

    - [src/mongo/util/net/ssl\_manager.cpp](../../../ssl)

<div></div>

    mongo::prettyHostName()

- Used By:

    - [src/mongo/db/commands/dbhash.cpp](../../../database\_commands)
    - [src/mongo/db/dbwebserver.cpp](../../../web\_server)
    - [src/mongo/db/lasterror.cpp](../../../cpp\_client\_driver)
    - [src/mongo/db/commands/server\_status.cpp](../../../database\_commands)
    - [src/mongo/db/dbcommands\_generic.cpp](../../../database\_commands)
    - [src/mongo/s/d\_logic.cpp](../../../writeback\_listener)
    - [src/mongo/db/repl/replset\_web\_handler.cpp](../../../replication)

<div></div>

    mongo::Socket::send(char const*, int, char const*)

- Used By:

    - [src/mongo/util/net/miniwebserver.cpp](../../../web\_server)
    - [src/mongo/util/net/httpclient.cpp](../../../rest\_client)

<div></div>

    mongo::Socket::~Socket()

- Used By:

    - [src/mongo/util/net/httpclient.cpp](../../../rest\_client)

<div></div>

    mongo::Socket::isStillConnected()

- Used By:

    - [src/mongo/client/dbclient.cpp](../../../cpp\_client\_driver)
    - [src/mongo/dbtests/mock/mock\_dbclient\_connection.cpp](../../../unit\_tests)

<div></div>

    mongo::unknownAddress

- Used By:

    - [src/mongo/dbtests/querytests.cpp](../../../unit\_tests)

<div></div>

    mongo::portSendFlags

- Used By:

    - [src/mongo/util/net/ssl\_manager.cpp](../../../ssl)

<div></div>

    mongo::Socket::Socket(double, mongo::logger::LogSeverity)

- Used By:

    - [src/mongo/util/net/httpclient.cpp](../../../rest\_client)

<div></div>

    mongo::SockAddr::isLocalHost() const

- Used By:

    - [src/mongo/db/dbwebserver.cpp](../../../web\_server)

<div></div>

    mongo::Socket::setTimeout(double)

- Used By:

    - [src/mongo/util/net/miniwebserver.cpp](../../../web\_server)

<div></div>

    mongo::Socket::connect(mongo::SockAddr&)

- Used By:

    - [src/mongo/client/dbclient.cpp](../../../cpp\_client\_driver)
    - [src/mongo/util/net/httpclient.cpp](../../../rest\_client)

<div></div>

    mongo::getHostNameCached()

- Used By:

    - [src/mongo/s/commands\_admin.cpp](../../../sharding)
    - [src/mongo/s/version\_mongos.cpp](../../../sharding)
    - [src/mongo/db/db.cpp](../../../mongos\_and\_mongod\_mains)
    - [src/mongo/s/balance.cpp](../../../sharding)
    - [src/mongo/s/config.cpp](../../../sharding)
    - [src/mongo/db/query/new\_find.cpp](../../../core\_query\_system)
    - [src/mongo/db/log\_process\_details.cpp](../../../logging\_system)
    - [src/mongo/s/cluster\_client\_internal.cpp](../../../sharding)

<div></div>

    mongo::enableIPv6(bool)

- Used By:

    - [src/mongo/tools/tool\_options.cpp](../../../tools)
    - [src/mongo/s/mongos\_options.cpp](../../../mongos\_and\_mongod\_mains)
    - [src/mongo/shell/shell\_options.cpp](../../../mongo\_shell)
    - [src/mongo/db/mongod\_options.cpp](../../../mongos\_and\_mongod\_mains)

<div></div>

    mongo::Socket::secure(mongo::SSLManagerInterface*, std::string const&)

- Used By:

    - [src/mongo/client/dbclient.cpp](../../../cpp\_client\_driver)
    - [src/mongo/util/net/httpclient.cpp](../../../rest\_client)

<div></div>

    mongo::SockAddr::getAddr() const

- Used By:

    - [src/mongo/client/dbclient.cpp](../../../cpp\_client\_driver)

<div></div>

    mongo::SockAddr::toString(bool) const

- Used By:

    - [src/mongo/tools/bridge.cpp](../../../tools)
    - [src/mongo/dbtests/querytests.cpp](../../../unit\_tests)
    - [src/mongo/util/net/ssl\_manager.cpp](../../../ssl)

<div></div>

    mongo::IPv6Enabled()

- Used By:

    - [src/mongo/db/commands/isself.cpp](../../../database\_commands)

<div></div>

    mongo::SockAddr::SockAddr(char const*, int)

- Used By:

    - [src/mongo/client/dbclient.cpp](../../../cpp\_client\_driver)
    - [src/mongo/util/net/httpclient.cpp](../../../rest\_client)

<div></div>

    vtable for mongo::SocketException

- Used By:

    - [src/mongo/client/dbclient.cpp](../../../cpp\_client\_driver)
    - [src/mongo/dbtests/mock/mock\_remote\_db\_server.cpp](../../../unit\_tests)
    - [src/mongo/client/connpool.cpp](../../../cpp\_client\_driver)
    - [src/mongo/util/net/ssl\_manager.cpp](../../../ssl)

<div></div>

    mongo::Socket::handleSendError(int, char const*)

- Used By:

    - [src/mongo/util/net/ssl\_manager.cpp](../../../ssl)

<div></div>

    mongo::Socket::handleRecvError(int, int)

- Used By:

    - [src/mongo/util/net/ssl\_manager.cpp](../../../ssl)

<div></div>

    mongo::Socket::close()

- Used By:

    - [src/mongo/util/net/miniwebserver.cpp](../../../web\_server)

<div></div>

    mongo::getHostName()

- Used By:

    - [src/mongo/s/config.cpp](../../../sharding)
    - [src/mongo/shell/shell\_utils\_extended.cpp](../../../mongo\_shell)
    - [src/mongo/db/repl/rs\_initiate.cpp](../../../replication)
    - [src/mongo/db/repl/sync\_source\_feedback.cpp](../../../replication)
    - [src/mongo/db/repl/oplogreader.cpp](../../../replication)
    - [src/mongo/db/repl/master\_slave.cpp](../../../replication)
    - [src/mongo/s/distlock.cpp](../../../sharding)
    - [src/mongo/dbtests/perftests.cpp](../../../unit\_tests)
    - [src/mongo/dbtests/replsettests.cpp](../../../unit\_tests)

<div></div>

    mongo::Socket::doSSLHandshake(char const*, int)

- Used By:

    - [src/mongo/util/net/miniwebserver.cpp](../../../web\_server)