
# Interface for BSON Timestamp
This interface information represents symbols that are defined in this group but used in other modules.  Does not include symbols defined in this group that are used inside this module.

### src/mongo/bson/optime.cpp

<div></div>

    mongo::OpTime::last

- Used By:

    - [src/mongo/db/repl/oplog.cpp](../../../../replication/data\_sync)
    - [src/mongo/db/repl/rs.cpp](../../../../replication/replica\_set\_state)

<div></div>

    mongo::OpTime::now(mongo::mutex::scoped_lock const&)

- Used By:

    - [src/mongo/db/repl/oplog.cpp](../../../../replication/data\_sync)
    - [src/mongo/db/ops/modifier\_current\_date.cpp](../../../../queries/update\_system)
    - [src/mongo/db/dbcommands.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/ops/insert.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/dbtests/replsettests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/ops/modifier\_object\_replace.cpp](../../../../queries/update\_system)

<div></div>

    mongo::OpTime::notifier

- Used By:

    - [src/mongo/db/repl/oplog.cpp](../../../../replication/data\_sync)
    - [src/mongo/db/repl/rs.cpp](../../../../replication/replica\_set\_state)

<div></div>

    mongo::OpTime::m

- Used By:

    - [src/mongo/db/repl/oplog.cpp](../../../../replication/data\_sync)
    - [src/mongo/db/repl/rs.cpp](../../../../replication/replica\_set\_state)
    - [src/mongo/db/ops/modifier\_current\_date.cpp](../../../../queries/update\_system)
    - [src/mongo/db/instance.cpp](../../../../storage/storage\_layer\_structure)
    - [src/mongo/db/dbcommands.cpp](../../../../queries/database\_commands)
    - [src/mongo/db/ops/insert.cpp](../../../../queries/core\_query\_system)
    - [src/mongo/dbtests/replsettests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/db/ops/modifier\_object\_replace.cpp](../../../../queries/update\_system)

<div></div>

    mongo::OpTime::_now()

- Used By:

    - [src/mongo/dbtests/replsettests.cpp](../../../../tests/unit\_tests)
    - [src/mongo/dbtests/querytests.cpp](../../../../tests/unit\_tests)

<div></div>

    mongo::OpTime::max()

- Used By:

    - [src/mongo/scripting/v8\_db.cpp](../../../../javascript/javascript\_libraries)
    - [src/mongo/dbtests/jstests.cpp](../../../../tests/unit\_tests)

<div></div>

    mongo::OpTime::waitForDifferent(unsigned int)

- Used By:

    - [src/mongo/db/instance.cpp](../../../../storage/storage\_layer\_structure)

<div></div>

    mongo::OpTime::getLast(mongo::mutex::scoped_lock const&)

- Used By:

    - [src/mongo/db/instance.cpp](../../../../storage/storage\_layer\_structure)