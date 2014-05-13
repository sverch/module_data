# Mongod And Mongos Command Line Options
Command line options for mongod and mongos that are not connected to a specific module.


-------------

## Server Options
Command line options shared between mongod and mongos, such as some basic network options

#### Files
- src/mongo/db/server\_options.cpp   (mongod, tools, mongos)
- src/mongo/db/server\_options.h   (mongod, tools, mongos)
- src/mongo/db/server\_options\_helpers.cpp   (mongod, tools, mongos)
- src/mongo/db/server\_options\_helpers.h   (mongod, tools, mongos)
- src/mongo/db/server\_options\_test.cpp   ()

#### [Interface](interface/0)

#### [Dependencies](dependencies/0)

-------------

## Mongod Options
Mongod command line options

#### Files
- src/mongo/db/mongod\_options.cpp   (mongod)
- src/mongo/db/mongod\_options.h   (mongod, tools)
- src/mongo/db/mongod\_options\_init.cpp   (mongod)

#### [Interface](interface/1)

#### [Dependencies](dependencies/1)

-------------

## Mongos Options
Mongos command line options

#### Files
- src/mongo/s/mongos\_options.cpp   (mongos)
- src/mongo/s/mongos\_options.h   (mongod, tools, mongos)
- src/mongo/s/mongos\_options\_init.cpp   (mongos)

#### [Interface](interface/2)

#### [Dependencies](dependencies/2)