
# Interface for Thread Name
This interface information represents symbols that are defined in this group but used in other modules.  Does not include symbols defined in this group that are used inside this module.

### src/mongo/util/concurrency/thread\_name.cpp

<div></div>

    mongo::setThreadName(mongo::StringData)

- Used By:

    - [src/mongo/util/file\_allocator.cpp](../../../../storage/file\_allocation)
    - [src/mongo/s/server.cpp](../../../../process\_management/mongos\_and\_mongod\_mains)
    - [src/mongo/db/client.cpp](../../../../queries/client\_and\_operation\_tracking)
    - [src/mongo/util/net/message\_server\_port.cpp](../../../../network/network\_core)
    - [src/mongo/s/distlock.cpp](../../../../sharding/cluster\_locking)
    - [src/mongo/s/s\_only.cpp](../../../../queries/client\_and\_operation\_tracking)

<div></div>

    mongo::getThreadName()

- Used By:

    - [src/mongo/client/dbclientcursor.cpp](../../../../network/cpp\_client\_driver)
    - [src/mongo/util/net/listen.cpp](../../../../network/network\_core)
    - [src/mongo/db/pipeline/document\_source\_sort.cpp](../../../../queries/aggregation\_framework)
    - [src/mongo/db/structure/btree/btree.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/mongod\_options.cpp](../../../../process\_management/mongos\_and\_mongod\_mains)
    - [src/mongo/db/auth/authorization\_manager.cpp](../../../../security/authorization)
    - [src/mongo/db/commands/cleanup\_orphaned\_cmd.cpp](../../../../queries/database\_commands)
    - [src/mongo/s/balancer\_policy.cpp](../../../../sharding/balancer)
    - [src/mongo/unittest/temp\_dir.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/query/plan\_enumerator.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/exec/count.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/query/get\_runner.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/catalog/index\_create.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/repl/write\_concern.cpp](../../../../replication/write\_concern)
    - [src/mongo/db/commands/auth\_schema\_upgrade\_d.cpp](../../../../security/authorization)
    - [src/mongo/dbtests/framework.cpp](../../../../tests/unit\_tests)
    - [src/mongo/client/dbclient\_rs.cpp](../../../../network/cpp\_client\_driver)
    - [src/mongo/util/net/sock.cpp](../../../../network/network\_core)
    - [src/mongo/s/cluster\_client\_internal.cpp](../../../../sharding/config\_metadata\_upgrade)
    - [src/mongo/db/range\_deleter\_db\_env.cpp](../../../../sharding/chunk\_management)
    - [src/mongo/db/index/btree\_index\_cursor.cpp](../../../../queries/indexing)
    - [src/mongo/db/commands/fsync.cpp](../../../../queries/database\_commands)
    - [src/mongo/s/balance.cpp](../../../../sharding/balancer)
    - [src/mongo/db/repl/rs\_initialsync.cpp](../../../../replication/data\_sync)
    - [src/mongo/db/exec/index\_scan.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/tests.cpp](../../../../dead\_code/dead\_code)
    - [src/mongo/dbtests/perftests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/s/chunk\_manager\_targeter.cpp](../../../../sharding/routing)
    - [src/mongo/dbtests/namespacetests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/client/replica\_set\_monitor.cpp](../../../../network/cpp\_client\_driver)
    - [src/mongo/db/fts/fts\_command\_mongos.cpp](../../../../queries/full\_text\_search\_module)
    - [src/mongo/s/mongos\_options.cpp](../../../../process\_management/mongos\_and\_mongod\_mains)
    - [src/mongo/db/repl/manager.cpp](../../../../replication/replica\_set\_state)
    - [src/mongo/db/pipeline/document\_source\_out.cpp](../../../../queries/aggregation\_framework)
    - [src/mongo/db/catalog/database.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/repl/rs.cpp](../../../../replication/replica\_set\_state)
    - [src/mongo/db/dur\_preplogbuffer.cpp](../../../../storage/journaling)
    - [src/mongo/dbtests/config\_server\_fixture.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/structure/record\_store.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/auth/auth\_index\_d.cpp](../../../../security/authorization)
    - [src/mongo/db/auth/authz\_manager\_external\_state\_d.cpp](../../../../security/authorization)
    - [src/third\_party/s2/base/logging.cc](../../../../third\_party/s2)
    - [src/mongo/db/queryutil.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/commands/find\_and\_modify.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/log\_process\_details.cpp](../../../../process\_management/logging\_system)
    - [src/mongo/util/net/message\_server\_port.cpp](../../../../network/network\_core)
    - [src/mongo/db/query/plan\_ranker.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/dur\_journal.cpp](../../../../storage/journaling)
    - [src/mongo/db/startup\_warnings.cpp](../../../../process\_management/startup\_initialization)
    - [src/mongo/db/index/2d\_access\_method.cpp](../../../../queries/indexing)
    - [src/mongo/db/index\_builder.cpp](../../../../queries/indexing)
    - [src/mongo/s/write\_ops/batch\_write\_exec.cpp](../../../../network/write\_commands)
    - [src/mongo/db/index/haystack\_access\_method.cpp](../../../../queries/indexing)
    - [src/mongo/util/log.cpp](../../../../process\_management/logging\_system)
    - [src/mongo/db/repl/replset\_commands.cpp](../../../../replication/replication\_commands)
    - [src/mongo/db/index/fts\_access\_method.cpp](../../../../queries/indexing)
    - [src/mongo/db/query/plan\_executor.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/db.cpp](../../../../process\_management/mongos\_and\_mongod\_mains)
    - [src/mongo/db/commands/write\_commands/batch\_executor.cpp](../../../../network/write\_commands)
    - [src/mongo/util/mmap.cpp](../../../../storage/mmap)
    - [src/mongo/db/exec/text.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/dbcommands.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/exec/collection\_scan.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/client/clientAndShell.cpp](../../../../network/cpp\_client\_driver)
    - [src/mongo/db/commands/parameters.cpp](../../../../queries/database\_commands)
    - [src/mongo/client/syncclusterconnection.cpp](../../../../network/cpp\_client\_driver)
    - [src/mongo/util/file\_allocator.cpp](../../../../storage/file\_allocation)
    - [src/mongo/db/range\_deleter.cpp](../../../../sharding/chunk\_management)
    - [src/mongo/db/structure/catalog/namespace\_index.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/commands/dbhash.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/commands/rename\_collection.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/lasterror.cpp](../../../../network/network\_core)
    - [src/mongo/db/catalog/collection\_info\_cache.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/pagefault.cpp](../../../../storage/page\_fault\_utilities)
    - [src/mongo/db/dbcommands\_generic.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/query/new\_find.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/dur\_commitjob.cpp](../../../../storage/journaling)
    - [src/mongo/db/commands/drop\_indexes.cpp](../../../../queries/database\_commands)
    - [src/mongo/s/config\_upgrade.cpp](../../../../sharding/config\_metadata\_upgrade)
    - [src/mongo/db/catalog/index\_catalog.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/catalog/index\_catalog\_entry.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/cloner.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/dbtests/replsettests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/s/config\_upgrade\_helpers.cpp](../../../../sharding/config\_metadata\_upgrade)
    - [src/mongo/dbtests/documentsourcetests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/s/writeback\_listener.cpp](../../../../sharding/writeback\_listener)
    - [src/mongo/db/fts/fts\_enabled.cpp](../../../../queries/full\_text\_search\_module)
    - [src/mongo/db/geo/geoquery.cpp](../../../../queries/geo\_queries)
    - [src/mongo/db/repl/health.cpp](../../../../replication/replica\_set\_state)
    - [src/mongo/db/pipeline/document\_source\_group.cpp](../../../../queries/aggregation\_framework)
    - [src/mongo/util/logfile.cpp](../../../../storage/journaling)
    - [src/mongo/dbtests/threadedtests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/util/mmap\_posix.cpp](../../../../storage/mmap)
    - [src/mongo/db/jsobj.cpp](../../../../bson/bson)
    - [src/mongo/scripting/engine\_v8.cpp](../../../../javascript/javascript\_libraries)
    - [src/mongo/db/prefetch.cpp](../../../../storage/page\_fault\_utilities)
    - [src/third\_party/s2/s2polyline.cc](../../../../third\_party/s2)
    - [src/mongo/util/net/ssl\_manager.cpp](../../../../network/ssl)
    - [src/mongo/db/dur.cpp](../../../../storage/journaling)
    - [src/mongo/db/lockstate.cpp](../../../../queries/concurrency)
    - [src/mongo/client/connpool.cpp](../../../../network/cpp\_client\_driver)
    - [src/mongo/db/structure/collection\_compact.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/dbhelpers.cpp](../../../../queries/client\_and\_operation\_tracking)
    - [src/mongo/db/introspect.cpp](../../../../queries/client\_and\_operation\_tracking)
    - [src/mongo/db/query/index\_bounds\_builder.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/instance.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/repl/rs\_config.cpp](../../../../replication/replica\_set\_configuration)
    - [src/mongo/dbtests/perf/perftest.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/storage/record.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/pdfile.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/repl/oplog.cpp](../../../../replication/data\_sync)
    - [src/mongo/db/initialize\_server\_global\_state.cpp](../../../../process\_management/startup\_initialization)
    - [src/mongo/db/ops/delete.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/query/planner\_analysis.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/repl/rs\_initiate.cpp](../../../../replication/replica\_set\_configuration)
    - [src/mongo/s/shardkey.cpp](../../../../sharding/routing)
    - [src/mongo/s/commands\_admin.cpp](../../../../sharding/mongos\_commands)
    - [src/mongo/unittest/unittest.cpp](../../../../tests/unit\_tests)
    - [src/mongo/s/cluster\_write.cpp](../../../../sharding/routing)
    - [src/mongo/db/query/cached\_plan\_runner.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/index/s2\_access\_method.cpp](../../../../queries/indexing)
    - [src/mongo/db/query/stage\_builder.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/tools/files.cpp](../../../../tools/tools)
    - [src/mongo/db/kill\_current\_op.cpp](../../../../queries/client\_and\_operation\_tracking)
    - [src/mongo/s/s\_only.cpp](../../../../queries/client\_and\_operation\_tracking)
    - [src/mongo/db/repl/bgsync.cpp](../../../../replication/data\_sync)
    - [src/mongo/db/query/query\_planner.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/commands/authentication\_commands.cpp](../../../../security/authentication)
    - [src/mongo/db/repl/consensus.cpp](../../../../replication/consensus)
    - [src/mongo/db/index/btree\_access\_method.cpp](../../../../queries/indexing)
    - [src/mongo/db/structure/btree/btreebuilder.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/repl/sync\_source\_feedback.cpp](../../../../replication/data\_sync)
    - [src/mongo/db/repl/heartbeat.cpp](../../../../replication/replica\_set\_state)
    - [src/mongo/db/commands/plan\_cache\_commands.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/durop.cpp](../../../../storage/journaling)
    - [src/mongo/db/extsort.cpp](../../../../queries/aggregation\_framework)
    - [src/mongo/s/version\_manager.cpp](../../../../sharding/metadata\_versioning)
    - [src/mongo/dbtests/jsontests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/auth/user\_cache\_invalidator\_job.cpp](../../../../security/authorization)
    - [src/mongo/s/d\_writeback.cpp](../../../../sharding/writeback\_listener)
    - [src/mongo/scripting/bench.cpp](../../../../javascript/javascript\_libraries)
    - [src/mongo/db/commands/touch.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/server\_options\_helpers.cpp](../../../../process\_management/startup\_initialization)
    - [src/mongo/s/config.cpp](../../../../sharding/cluster\_metadata\_management)
    - [src/mongo/s/version\_mongos.cpp](../../../../process\_management/build\_information)
    - [src/mongo/db/structure/btree/key.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/geo/geoparser.cpp](../../../../queries/geo\_queries)
    - [src/mongo/db/exec/projection.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/commands/group.cpp](../../../../queries/database\_commands)
    - [src/mongo/s/d\_state.cpp](../../../../sharding/mongod\_sharding\_metadata)
    - [src/mongo/db/commands/get\_last\_error.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/structure/catalog/namespace\_details.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/index/hash\_access\_method.cpp](../../../../queries/indexing)
    - [src/mongo/db/storage/extent\_manager.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/s/metadata\_loader.cpp](../../../../sharding/mongod\_sharding\_metadata)
    - [src/mongo/client/parallel.cpp](../../../../sharding/routing)
    - [src/mongo/s/shardconnection.cpp](../../../../sharding/shard\_abstraction)
    - [src/mongo/db/commands.cpp](../../../../queries/database\_commands)
    - [src/mongo/s/commands\_public.cpp](../../../../sharding/mongos\_commands)
    - [src/mongo/scripting/v8\_utils.cpp](../../../../javascript/javascript\_libraries)
    - [src/mongo/db/query/planner\_ixselect.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/catalog/collection.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/query/planner\_access.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/query/plan\_cache.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/commands/collection\_to\_capped.cpp](../../../../queries/database\_commands)
    - [src/mongo/tools/stat.cpp](../../../../tools/tools)
    - [src/mongo/db/storage/extent.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/index/btree\_based\_access\_method.cpp](../../../../queries/indexing)
    - [src/mongo/db/exec/2dcommon.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/repl/sync.cpp](../../../../replication/data\_sync)
    - [src/mongo/db/storage/durable\_mapped\_file.cpp](../../../../storage/journaling)
    - [src/mongo/db/commands/geonear.cpp](../../../../queries/database\_commands)
    - [src/mongo/s/d\_migrate.cpp](../../../../sharding/chunk\_management)
    - [src/mongo/shell/shell\_utils\_launcher.cpp](../../../../mongo\_shell/mongo\_shell)
    - [src/mongo/s/client\_info.cpp](../../../../queries/client\_and\_operation\_tracking)
    - [src/mongo/util/net/ssl\_options.cpp](../../../../network/ssl)
    - [src/mongo/s/d\_merge.cpp](../../../../sharding/chunk\_management)
    - [src/mongo/db/repl/master\_slave.cpp](../../../../replication/master\_slave)
    - [src/mongo/db/projection.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/commands/server\_status.cpp](../../../../queries/database\_commands)
    - [src/mongo/s/chunk.cpp](../../../../sharding/chunk\_management)
    - [src/mongo/db/auth/authz\_manager\_external\_state\_s.cpp](../../../../security/authorization)
    - [src/mongo/db/ops/count.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/storage/data\_file.cpp](../../../../storage/mmap\_file\_interface)
    - [src/mongo/util/net/message\_port.cpp](../../../../network/network\_core)
    - [src/mongo/dbtests/repltests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/commands/mr.cpp](../../../../queries/database\_commands)
    - [src/mongo/tools/dump.cpp](../../../../tools/tools)
    - [src/mongo/db/repl/rs\_sync.cpp](../../../../replication/data\_sync)
    - [src/mongo/db/exec/s2near.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/s/collection\_metadata.cpp](../../../../sharding/mongod\_sharding\_metadata)
    - [src/mongo/tools/bridge.cpp](../../../../tools/tools)
    - [src/mongo/db/commands/test\_commands.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/auth/authz\_session\_external\_state\_server\_common.cpp](../../../../security/authorization)
    - [src/mongo/dbtests/counttests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/auth/authorization\_session.cpp](../../../../security/authorization)
    - [src/mongo/s/write\_ops/batch\_downconvert.cpp](../../../../network/write\_commands)
    - [src/mongo/db/repl/repl\_start.cpp](../../../../replication/replication\_initialization)
    - [src/mongo/scripting/engine.cpp](../../../../javascript/javascript\_libraries)
    - [src/mongo/db/commands/validate.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/catalog/database\_holder.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/repl/oplogreader.cpp](../../../../replication/data\_sync)
    - [src/mongo/bson/optime.cpp](../../../../bson/bson)
    - [src/mongo/s/server.cpp](../../../../process\_management/mongos\_and\_mongod\_mains)
    - [src/mongo/db/d\_concurrency.cpp](../../../../queries/concurrency)
    - [src/mongo/db/clientcursor.cpp](../../../../queries/client\_and\_operation\_tracking)
    - [src/mongo/dbtests/sharding.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/repl/rs\_rollback.cpp](../../../../replication/data\_sync)
    - [src/mongo/tools/import.cpp](../../../../tools/tools)
    - [src/mongo/db/index\_rebuilder.cpp](../../../../queries/indexing)
    - [src/mongo/util/file.cpp](../../../../storage/file\_interface)
    - [src/mongo/db/fts/fts\_command.cpp](../../../../queries/full\_text\_search\_module)
    - [src/mongo/db/query/multi\_plan\_runner.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/restapi.cpp](../../../../network/web\_server)
    - [src/mongo/db/ttl.cpp](../../../../queries/indexing)
    - [src/mongo/db/commands/isself.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/commands/compact.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/commands/index\_stats.cpp](../../../../queries/database\_commands)
    - [src/mongo/dbtests/indexcatalogtests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/dur\_writetodatafiles.cpp](../../../../storage/journaling)
    - [src/mongo/db/ops/update.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/s/d\_logic.cpp](../../../../sharding/writeback\_listener)
    - [src/mongo/s/distlock.cpp](../../../../sharding/cluster\_locking)
    - [src/mongo/s/balancer\_policy\_tests.cpp](../../../../sharding/balancer)
    - [src/mongo/s/d\_split.cpp](../../../../sharding/chunk\_management)
    - [src/mongo/s/config\_upgrade\_v0\_to\_v5.cpp](../../../../sharding/config\_metadata\_upgrade)
    - [src/mongo/db/exec/distinct\_scan.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/db/auth/user\_document\_parser.cpp](../../../../security/authorization)
    - [src/mongo/db/auth/authz\_manager\_external\_state\_local.cpp](../../../../security/authorization)
    - [src/mongo/dbtests/jstests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/dbeval.cpp](../../../../queries/database\_commands)
    - [src/mongo/s/shard.cpp](../../../../sharding/shard\_abstraction)
    - [src/mongo/s/cursors.cpp](../../../../sharding/routing)
    - [src/mongo/client/dbclient.cpp](../../../../network/cpp\_client\_driver)
    - [src/mongo/s/strategy.cpp](../../../../network/network\_core)
    - [src/mongo/s/grid.cpp](../../../../sharding/cluster\_metadata\_management)
    - [src/mongo/util/fail\_point.cpp](../../../../tests/fail\_points)
    - [src/mongo/shell/dbshell.cpp](../../../../mongo\_shell/mongo\_shell)
    - [src/mongo/util/net/miniwebserver.cpp](../../../../network/web\_server)
    - [src/mongo/db/dur\_recover.cpp](../../../../storage/journaling)
    - [src/mongo/dbtests/framework\_options.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/commands/storage\_details.cpp](../../../../queries/database\_commands)
    - [src/mongo/s/request.cpp](../../../../network/network\_core)
    - [src/mongo/db/auth/security\_key.cpp](../../../../security/authentication)