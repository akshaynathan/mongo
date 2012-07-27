MongoDB Error Codes
==========




src/mongo/bson/bson-inl.h
----
* 10065 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L178) 
* 10313 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L551) Insufficient bytes to calculate element size
* 10314 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L555) Insufficient bytes to calculate element size
* 10315 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L560) Insufficient bytes to calculate element size
* 10316 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L565) Insufficient bytes to calculate element size
* 10317 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L569) Insufficient bytes to calculate element size
* 10318 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L575) Invalid regex string
* 10319 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L585) Invalid regex options string
* 10320 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L659) 
* 10321 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L496) 
* 10322 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L501) Invalid CodeWScope size
* 10323 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L503) Invalid CodeWScope string size
* 10324 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L504) Invalid CodeWScope string size
* 10325 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L507) Invalid CodeWScope size
* 10326 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L509) Invalid CodeWScope object size
* 10327 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L458) Object does not end with EOO
* 10328 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L460) Invalid element size
* 10329 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L461) Element too large
* 10330 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L463) Element extends past end of object
* 10331 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L468) EOO Before end of object
* 10334 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L217) 
* 13655 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L593) 
* 16150 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson-inl.h#L680) 


src/mongo/bson/bson_db.h
----
* 10062 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bson_db.h#L60) not code


src/mongo/bson/bsonelement.h
----
* 10063 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonelement.h#L409) not a dbref
* 10064 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonelement.h#L414) not a dbref
* 10333 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonelement.h#L439) Invalid field name
* 13111 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonelement.h#L472) 
* 13118 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonelement.h#L477) unexpected or missing type value in BSON object
* 16177 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonelement.h#L265) not codeWScope
* 16178 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonelement.h#L272) not codeWScope


src/mongo/bson/bsonobjbuilder.h
----
* 10335 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonobjbuilder.h#L554) builder does not own memory
* 10336 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonobjbuilder.h#L629) No subobject started
* 13048 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonobjbuilder.h#L819) can't append to array using string field name [" + name.data() + "]
* 15891 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonobjbuilder.h#L827) can't backfill array to larger than 1,500,000 elements
* 16234 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/bsonobjbuilder.h#L417) Invalid call to appendNull in BSONObj Builder.


src/mongo/bson/ordering.h
----
* 13103 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/ordering.h#L64) too many compound keys


src/mongo/bson/util/builder.h
----
* 10000 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/util/builder.h#L108) out of memory BufBuilder
* 13548 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/util/builder.h#L220) 
* 15912 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/util/builder.h#L83) out of memory StackAllocator::Realloc
* 15913 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/util/builder.h#L133) out of memory BufBuilder::reset
* 16070 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/bson/util/builder.h#L224) out of memory BufBuilder::grow_reallocate


src/mongo/client/clientAndShell.cpp
----
* 10256 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/clientAndShell.cpp#L68) no createDirectClient in clientOnly


src/mongo/client/connpool.cpp
----
* 13071 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/connpool.cpp#L204) invalid hostname [" + host + "]
* 13328 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/connpool.cpp#L184) : connect failed " + url.toString() + " : 


src/mongo/client/connpool.h
----
* 11004 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/connpool.h#L246) connection was returned to the pool already
* 11005 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/connpool.h#L252) connection was returned to the pool already
* 13102 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/connpool.h#L258) connection was returned to the pool already


src/mongo/client/dbclient.cpp
----
* 10005 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L600) listdatabases failed" , runCommand( "admin" , BSON( "listDatabases
* 10006 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L601) listDatabases.databases not array" , info["databases
* 10007 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L992) dropIndex failed
* 10008 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L999) dropIndexes failed
* 10276 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L662) DBClientBase::findN: transport error: " << getServerAddress() << " ns: " << ns << " query: 
* 10278 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L1136) dbclient error communicating with server: 
* 10337 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L1087) object not valid
* 11010 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L375) count fails:
* 13386 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L843) socket error for mapping query
* 13421 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L147) trying to connect to invalid ConnectionString
* 16090 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L815) socket error for mapping query
* 16335 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient.cpp#L134) custom connection to 


src/mongo/client/dbclient_rs.cpp
----
* 10009 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient_rs.cpp#L299) ReplicaSetMonitor no master found for set: 
* 13610 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient_rs.cpp#L238) ConfigChangeHook already specified
* 13639 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient_rs.cpp#L1044) can't connect to new replica set master [" << _masterHost.toString() << "] err: 
* 13642 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient_rs.cpp#L100) need at least 1 node for a replica set
* 15899 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient_rs.cpp#L372) No suitable secondary found for slaveOk query in replica set: 
* 16337 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient_rs.cpp#L932) Unknown read preference
* 16340 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclient_rs.cpp#L1012) No replica set monitor active and no cached seed 


src/mongo/client/dbclientcursor.cpp
----
* 13127 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclientcursor.cpp#L180) getMore: cursor didn't exist on server, possible restart or timeout?
* 13422 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclientcursor.cpp#L234) DBClientCursor next() called but more() is false
* 14821 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclientcursor.cpp#L300) No client or lazy client specified, cannot store multi-host connection.
* 15875 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclientcursor.cpp#L81) DBClientCursor::initLazy called on a client that doesn't support lazy


src/mongo/client/dbclientcursor.h
----
* 13106 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclientcursor.h#L80) 
* 13348 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclientcursor.h#L233) connection died
* 13383 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclientcursor.h#L250) BatchIterator empty


src/mongo/client/dbclientinterface.h
----
* 10011 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclientinterface.h#L663) no collection name
* 9000 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/dbclientinterface.h#L1002) 


src/mongo/client/distlock.cpp
----
* 14023 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/distlock.cpp#L617) remote time in cluster " << _conn.toString() << " is now skewed, cannot force lock.
* 16060 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/distlock.cpp#L130) cannot query locks collection on config server 


src/mongo/client/distlock_test.cpp
----
* 13678 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/distlock_test.cpp#L386) Could not communicate with server " << server.toString() << " in cluster " << cluster.toString() << " to change skew by 


src/mongo/client/gridfs.cpp
----
* 10012 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/gridfs.cpp#L99) file doesn't exist" , fileName == "-
* 10013 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/gridfs.cpp#L106) error opening file
* 10014 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/gridfs.cpp#L219) chunk is empty!
* 10015 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/gridfs.cpp#L251) doesn't exists
* 13296 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/gridfs.cpp#L69) invalid chunk size is specified
* 13325 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/gridfs.cpp#L245) couldn't open file: 
* 9008 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/gridfs.cpp#L145) filemd5 failed


src/mongo/client/model.cpp
----
* 10016 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/model.cpp#L40) _id isn't set - needed for remove()" , _id["_id
* 13121 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/model.cpp#L84) 
* 9002 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/model.cpp#L53) error on Model::remove: 
* 9003 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/model.cpp#L126) error on Model::save: 


src/mongo/client/parallel.cpp
----
* 10017 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L102) cursor already done
* 10018 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L414) no more items
* 10019 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L1573) no more elements
* 13431 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L502) have to have sort key in projection and removing it
* 13633 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L132) error querying server: 
* 14812 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L1650) Error running command on server: 
* 14813 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L1651) Command returned nothing
* 15986 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L810) too many retries in total
* 15987 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L932) could not fully initialize cursor on shard 
* 15988 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L1069) error querying server
* 15989 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/parallel.cpp#L776) database not found for parallel cursor request


src/mongo/client/syncclusterconnection.cpp
----
* 10022 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L275) SyncClusterConnection::getMore not supported yet
* 10023 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L297) SyncClusterConnection bulk insert not implemented
* 13053 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L414) help failed: " << info , _commandOnActive( "admin" , BSON( name << "1" << "help
* 13054 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L234) write $cmd not supported in SyncClusterConnection::query for:
* 13104 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L175) SyncClusterConnection::findOne prepare failed: 
* 13105 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L193) 
* 13119 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L282) SyncClusterConnection::insert obj has to have an _id: 
* 13120 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L315) SyncClusterConnection::update upsert query needs _id" , query.obj["_id
* 13397 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L390) SyncClusterConnection::say prepare failed: 
* 15848 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L205) sync cluster of sync clusters?
* 8001 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L140) SyncClusterConnection write op failed: 
* 8002 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L271) all servers down!
* 8003 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L287) SyncClusterConnection::insert prepare failed: 
* 8004 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L54) SyncClusterConnection needs 3 servers
* 8005 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L321) SyncClusterConnection::udpate prepare failed: 
* 8006 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L364) SyncClusterConnection::call can only be used directly for dbQuery
* 8007 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L368) SyncClusterConnection::call can't handle $cmd" , strstr( d.getns(), "$cmd
* 8008 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L384) all servers down!
* 8020 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/client/syncclusterconnection.cpp#L303) SyncClusterConnection::remove prepare failed: 


src/mongo/db/btree.cpp
----
* 10281 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btree.cpp#L144) verify is misdefined
* 10282 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btree.cpp#L325) n==0 in btree popBack()
* 10283 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btree.cpp#L332) rchild not null in btree popBack()
* 10285 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btree.cpp#L1773) _insert: reuse key but lchild is not null
* 10286 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btree.cpp#L1774) _insert: reuse key but rchild is not null
* 10287 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btree.cpp#L85) btree: key+recloc already in index
* 15898 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btree.cpp#L43) error in index possibly corruption consider repairing 


src/mongo/db/btree.h
----
* 13000 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btree.h#L364) invalid keyNode: " +  BSON( "i" << i << "n


src/mongo/db/btreebuilder.cpp
----
* 10288 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btreebuilder.cpp#L76) bad key order in BtreeBuilder - server internal error


src/mongo/db/btreecursor.cpp
----
* 14800 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btreecursor.cpp#L224) unsupported index version 
* 15850 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/btreecursor.cpp#L70) keyAt bucket deleted


src/mongo/db/cap.cpp
----
* 10345 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cap.cpp#L266) passes >= maxPasses in capped collection alloc
* 13415 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cap.cpp#L352) emptying the collection is not allowed
* 13424 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cap.cpp#L419) collection must be capped
* 13425 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cap.cpp#L420) background index build in progress
* 13426 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cap.cpp#L431) failed during index drop: 
* 16328 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cap.cpp#L200) document is larger than capped size 


src/mongo/db/client.cpp
----
* 10057 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/client.cpp#L327) 
* 14031 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/client.cpp#L303) Can't take a write lock while out of disk space
* 15928 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/client.cpp#L248) can't open a database from a nested read lock 
* 15929 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/client.cpp#L353) client access to index backing namespace prohibited
* 16107 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/client.cpp#L309) Don't have a lock on: 
* 16151 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/client.cpp#L86) 


src/mongo/db/clientcursor.cpp
----
* 16089 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/clientcursor.cpp#L769) 


src/mongo/db/clientcursor.h
----
* 12051 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/clientcursor.h#L96) clientcursor already in use? driver problem?
* 12521 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/clientcursor.h#L328) internal error: use of an unlocked ClientCursor


src/mongo/db/cloner.cpp
----
* 10024 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cloner.cpp#L92) bad ns field for index during dbcopy
* 10025 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cloner.cpp#L94) bad ns field for index during dbcopy [2]
* 10026 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cloner.cpp#L753) source namespace does not exist
* 10027 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cloner.cpp#L763) target namespace exists", cmdObj["dropTarget
* 10289 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cloner.cpp#L307) useReplAuth is not written to replication log
* 10290 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cloner.cpp#L387) 
* 13008 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cloner.cpp#L704) must call copydbgetnonce first
* 15908 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cloner.cpp#L244) 
* 15967 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cloner.cpp#L742) invalid collection name: 


src/mongo/db/cmdline.cpp
----
* 10033 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cmdline.cpp#L398) logpath has to be non-zero
* 16176 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cmdline.cpp#L516) 


src/mongo/db/commands.cpp
----
* 15962 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands.cpp#L36) need to specify namespace
* 15966 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands.cpp#L37) dbname not ok in Command::parseNsFullyQualified: " << dbname , dbname == nss.db || dbname == "admin


src/mongo/db/commands/distinct.cpp
----
* 10044 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/distinct.cpp#L117) distinct too big, 16mb cap


src/mongo/db/commands/document_source_cursor.cpp
----
* 16028 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/document_source_cursor.cpp#L75) 


src/mongo/db/commands/find_and_modify.cpp
----
* 12515 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/find_and_modify.cpp#L207) can't remove and update", cmdObj["update
* 12516 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/find_and_modify.cpp#L239) must specify remove or update
* 13329 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/find_and_modify.cpp#L184) upsert mode requires update field
* 13330 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/find_and_modify.cpp#L185) upsert mode requires query field


src/mongo/db/commands/group.cpp
----
* 10041 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/group.cpp#L42) invoke failed in $keyf: 
* 10042 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/group.cpp#L44) return of $key has to be an object
* 10043 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/group.cpp#L123) group() can't handle more than 20000 unique keys
* 9010 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/group.cpp#L129) reduce invoke failed: 


src/mongo/db/commands/isself.cpp
----
* 13469 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/isself.cpp#L49) getifaddrs failure: 
* 13470 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/isself.cpp#L64) getnameinfo() failed: 
* 13472 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/isself.cpp#L110) getnameinfo() failed: 


src/mongo/db/commands/mr.cpp
----
* 10074 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L154) need values
* 10075 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L195) reduce -> multiple not supported yet
* 10076 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L508) rename failed: 
* 10077 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L962) fast_emit takes 2 args
* 13069 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L963) an emit can't be more than half max bson size
* 13070 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L175) value too large to reduce
* 13522 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L262) unknown out specifier [" << t << "]
* 13598 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L54) couldn't compile code for: 
* 13602 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L234) outType is no longer a valid option" , cmdObj["outType
* 13604 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L430) too much data for in memory map/reduce
* 13606 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L276) 'out' has to be a string or an object
* 13608 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L316) query has to be blank or an Object
* 13609 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L323) sort has to be blank or an Object
* 13630 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L360) userCreateNS failed for mr tempLong ns: " << _config.tempLong << " err: 
* 13631 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L346) userCreateNS failed for mr incLong ns: " << _config.incLong << " err: 
* 15876 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L1042) could not create cursor over " << config.ns << " to hold data while prepping m/r
* 15877 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L1044) could not create m/r holding client cursor over 
* 15895 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L272) nonAtomic option cannot be used with this output type
* 15921 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L414) splitVector failed: 
* 16052 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L1093) could not create cursor over " << config.ns << " for query : " << config.filter << " sort : 
* 16053 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L1095) could not create client cursor over " << config.ns << " for query : " << config.filter << " sort : 
* 16054 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L281) shardedFirstPass should only use replace outType
* 16149 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L1025) cannot run map reduce without the js engine
* 9014 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/mr.cpp#L72) map invoke failed: 


src/mongo/db/commands/pipeline.cpp
----
* 15942 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/pipeline.cpp#L154) pipeline element 
* 16029 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/pipeline.cpp#L436) 


src/mongo/db/commands/touch.cpp
----
* 16153 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/commands/touch.cpp#L96) namespace does not exist


src/mongo/db/compact.cpp
----
* 13660 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/compact.cpp#L301) namespace " << ns << " does not exist
* 13661 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/compact.cpp#L302) cannot compact capped collection
* 14024 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/compact.cpp#L115) compact error out of space during compaction
* 14025 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/compact.cpp#L232) compact error no space available to allocate
* 14027 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/compact.cpp#L293) can't compact a system namespace", !str::contains(ns, ".system.
* 14028 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/compact.cpp#L292) bad ns


src/mongo/db/curop.cpp
----
* 11600 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/curop.cpp#L188) interrupted at shutdown
* 11601 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/curop.cpp#L190) operation was interrupted


src/mongo/db/curop.h
----
* 12601 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/curop.h#L192) CurOp not marked done yet


src/mongo/db/cursor.h
----
* 13285 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cursor.h#L200) manual matcher config not allowed
* 16159 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/cursor.h#L211) manual keyFieldsOnly config not allowed


src/mongo/db/d_concurrency.cpp
----
* 16098 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L512) can't dblock:" << db << " when local or admin is already locked
* 16099 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L694) internal error tried to lock two databases at the same time. old:" << ls.otherName() << " new:
* 16100 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L699) can't dblock:" << db << " when local or admin is already locked
* 16103 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L123) can't lock_R, threadState=
* 16104 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L263) expected to be read locked for 
* 16105 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L269) expected to be write locked for 
* 16106 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L507) internal error tried to lock two databases at the same time. old:" << ls.otherName() << " new:
* 16114 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L132) 
* 16116 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L333) 
* 16117 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L334) 
* 16118 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L337) 
* 16119 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L347) 
* 16120 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L348) 
* 16121 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L355) 
* 16122 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L357) 
* 16123 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L358) 
* 16125 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L362) 
* 16126 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L364) 
* 16127 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L370) 
* 16128 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L372) 
* 16129 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L376) 
* 16130 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L378) 
* 16131 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L474) 
* 16132 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L479) 
* 16133 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L493) 
* 16134 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L527) 
* 16135 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L713) 
* 16171 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L294) 
* 16186 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L550) can't get a DBWrite while having a read lock
* 16187 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L719) 
* 16188 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L727) 
* 16189 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L732) 
* 16252 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L500) 
* 16253 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L541) 
* 16254 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L577) 
* 16255 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/d_concurrency.cpp#L687) 


src/mongo/db/database.cpp
----
* 10028 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L69) db name is empty
* 10029 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L71) bad db name [1]
* 10030 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L72) bad db name [2]
* 10031 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L73) bad char(s) in db name
* 10032 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L70) db name too long
* 10295 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L241) getFile(): bad file number value (corrupt db?): run repair
* 12501 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L325) quota exceeded
* 14810 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L340) couldn't allocate space (suitableFile)
* 15924 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L189) getFile(): bad file number value " << n << " (corrupt db?): run repair
* 15927 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L439) can't open database in a read lock. if db was just closed, consider retrying the query. might otherwise indicate an internal error
* 16185 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/database.cpp#L84) 


src/mongo/db/databaseholder.h
----
* 13074 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/databaseholder.h#L94) db name can't be empty
* 13075 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/databaseholder.h#L97) db name can't be empty
* 13280 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/databaseholder.h#L88) invalid db name: 


src/mongo/db/db.cpp
----
* 10296 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/db.cpp#L486) 
* 10297 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/db.cpp#L1413) Couldn't register Windows Ctrl-C handler
* 12590 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/db.cpp#L491) 
* 14026 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/db.cpp#L308) 


src/mongo/db/db.h
----
* 10298 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/db.h#L40) can't temprelease nested lock


src/mongo/db/dbcommands.cpp
----
* 10039 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L745) can't drop collection with reserved $ character in name
* 10040 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L1098) chunks out of order
* 10301 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L1498) source collection " + fromNs + " does not exist
* 13049 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L1635) godinsert must specify a collection
* 13281 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L1121) File deleted during filemd5 command
* 13416 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L1771) captrunc must specify a collection
* 13417 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L1779) captrunc collection not found or empty
* 13418 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L1781) captrunc invalid n
* 13428 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L1799) emptycapped must specify a collection
* 13429 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L1802) emptycapped no such collection
* 13455 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L321) dbexit timed out getting lock
* 14832 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L811) specify size:<n> when capped is true", !cmdObj["capped"].trueValue() || cmdObj["size"].isNumber() || cmdObj.hasField("$nExtents
* 15880 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L646) no ram log for warnings?
* 15888 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L808) must pass name of collection to create
* 16247 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands.cpp#L1060) md5 state not correct size


src/mongo/db/dbcommands_generic.cpp
----
* 10038 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands_generic.cpp#L414) forced error
* 16175 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbcommands_generic.cpp#L343) 


src/mongo/db/dbeval.cpp
----
* 10046 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbeval.cpp#L41) eval needs Code
* 12598 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbeval.cpp#L122) $eval reads unauthorized


src/mongo/db/dbhelpers.cpp
----
* 13430 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbhelpers.cpp#L131) no _id index
* 16333 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbhelpers.cpp#L243) 
* 16341 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbhelpers.cpp#L237) 


src/mongo/db/dbmessage.h
----
* 10304 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbmessage.h#L199) Client Error: Remaining data too small for BSON object
* 10305 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbmessage.h#L201) Client Error: Invalid object size
* 10306 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbmessage.h#L202) Client Error: Next object larger than space left in message
* 10307 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbmessage.h#L205) Client Error: bad object in message
* 13066 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbmessage.h#L197) Message contains no documents


src/mongo/db/dbwebserver.cpp
----
* 13453 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dbwebserver.cpp#L170) server not started with --jsonp


src/mongo/db/dur.cpp
----
* 13599 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur.cpp#L424) Written data does not match in-memory view. Missing WriteIntent?
* 13616 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur.cpp#L200) can't disable durability with pending writes
* 16110 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur.cpp#L261) 


src/mongo/db/dur_journal.cpp
----
* 13611 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_journal.cpp#L542) can't read lsn file in journal directory : 
* 13614 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_journal.cpp#L509) unexpected version number of lsn file in journal/ directory got: 
* 15926 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_journal.cpp#L357) Insufficient free space for journals


src/mongo/db/dur_recover.cpp
----
* 13531 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L79) unexpected files in journal directory " << dir.string() << " : 
* 13532 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L86) 
* 13533 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L162) problem processing journal file during recovery
* 13535 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L467) recover abrupt journal file end
* 13536 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L394) journal version number mismatch 
* 13537 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L385) 
* 13544 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L449) recover error couldn't open 
* 13545 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L474) --durOptions " << (int) CmdLine::DurScanOnly << " (scan only) specified
* 13594 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L358) journal checksum doesn't match
* 13622 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L255) Trying to write past end of file in WRITETODATAFILES
* 15874 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/dur_recover.cpp#L114) couldn't uncompress journal section


src/mongo/db/durop.cpp
----
* 13546 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/durop.cpp#L53) journal recover: unrecognized opcode in journal 
* 13547 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/durop.cpp#L144) recover couldn't create file 
* 13628 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/durop.cpp#L158) recover failure writing file 


src/mongo/db/extsort.cpp
----
* 10048 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/extsort.cpp#L102) already sorted
* 10049 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/extsort.cpp#L127) sorted already
* 10050 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/extsort.cpp#L148) bad
* 10308 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/extsort.cpp#L259) mmap failed


src/mongo/db/extsort.h
----
* 10052 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/extsort.h#L105) not sorted


src/mongo/db/geo/2d.cpp
----
* 13022 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L120) can't have 2 geo field
* 13023 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L121) 2d has to be first in index
* 13024 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L130) no geo field specified
* 13026 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L333) geo values have to be numbers: 
* 13027 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L356) point not in interval of [ " << _min << ", " << _max << " ]
* 13028 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L134) bits in geo index must be between 1 and 32
* 13042 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2866) missing geo field (" + _geo + ") in : 
* 13046 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2922) 'near' param missing/invalid", !cmdObj["near
* 13057 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2832) $within has to take an object or array
* 13058 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2856) unknown $within information : " << context << ", a shape must be specified.
* 13059 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2842) $center has to take an object or array
* 13060 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2503) $center needs 2 fields (middle,max distance)
* 13061 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2517) need a max distance >= 0 
* 13063 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2621) $box needs 2 fields (bottomLeft,topRight)
* 13064 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2633) need an area > 0 
* 13065 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2847) $box has to take an object or array
* 13067 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L328) geo field is empty
* 13068 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L330) geo field only has 1 element
* 13460 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2540) invalid $center query type: 
* 13461 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2528) Spherical MaxDistance > PI. Are you sure you are using radians?
* 13462 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2535) Spherical distance would require wrapping, which isn't implemented yet
* 13464 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2801) invalid $near search type: 
* 13654 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L249) location object expected, location array not in correct format
* 13656 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2508) the first field of $center object must be a location object
* 14029 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2852) $polygon has to take an object or array
* 14030 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/2d.cpp#L2716) polygon must be defined by three points or more


src/mongo/db/geo/core.h
----
* 13047 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/core.h#L106) wrong type for geo index. if you're using a pre-release version, need to rebuild index
* 14808 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/core.h#L509) point " << p.toString() << " must be in earth-like bounds of long : [-180, 180], lat : [-90, 90] 


src/mongo/db/geo/haystack.cpp
----
* 13314 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L89) can't have 2 geo fields
* 13315 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L90) 2d has to be first in index
* 13316 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L99) no geo field specified
* 13317 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L100) no other fields specified
* 13318 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L298) near needs to be an array
* 13319 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L299) maxDistance needs a number
* 13320 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L300) search needs to be an object
* 13321 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L80) need bucketSize
* 13322 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L106) not a number
* 13323 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L141) latlng not an array
* 13326 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/geo/haystack.cpp#L101) quadrant search can only have 1 other field for now


src/mongo/db/hashindex.cpp
----
* 16241 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/hashindex.cpp#L34) Currently only single field hashed index supported.
* 16242 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/hashindex.cpp#L36) Currently hashed indexes cannot guarantee uniqueness. Use a regular index.
* 16243 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/hashindex.cpp#L56) error: no hashed index field
* 16244 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/hashindex.cpp#L75) Error: hashed indexes do not currently support array values
* 16245 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/hashindex.cpp#L161) Only HashVersion 0 has been defined


src/mongo/db/index.cpp
----
* 10096 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.cpp#L304) invalid ns to index
* 10097 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.cpp#L305) bad table to index name on add index attempt current db: " << cc().database()->name << "  source: 
* 10098 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.cpp#L312) 
* 11001 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.cpp#L93) 
* 12504 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.cpp#L319) 
* 12505 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.cpp#L349) 
* 12523 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.cpp#L300) no index name specified
* 12524 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.cpp#L309) index key pattern too large
* 12588 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.cpp#L355) cannot add index with a background operation in progress
* 14803 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.cpp#L390) this version of mongod cannot build new indexes of version number 


src/mongo/db/index.h
----
* 14802 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index.h#L190) index v field should be Integer type


src/mongo/db/index_update.cpp
----
* 10092 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index_update.cpp#L269) too may dups on index build with dropDups=true
* 12584 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index_update.cpp#L422) cursor gone during bg index
* 12585 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index_update.cpp#L401) cursor gone during bg index; dropDups
* 13130 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index_update.cpp#L438) can't start bg index b/c in recursive lock (db.eval?)
* 16093 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/index_update.cpp#L393) after yield cursor deleted


src/mongo/db/indexkey.cpp
----
* 13007 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/indexkey.cpp#L65) can only have 1 index plugin / bad index key pattern
* 13529 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/indexkey.cpp#L82) sparse only works for single field keys
* 15855 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/indexkey.cpp#L299) Ambiguous field name found in array (do not use numeric field names in embedded elements in an array), field: '" << arrField.fieldName() << "' for array: 
* 15869 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/indexkey.cpp#L415) Invalid index version for key generation.


src/mongo/db/instance.cpp
----
* 10054 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L565) not master
* 10055 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L548) update object too large
* 10056 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L602) not master
* 10058 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L797) not master
* 10059 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L744) object to insert too large
* 10309 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L1116) Unable to create/open lock file: " << name << ' ' << errnoWithDescription() << " Is a mongod instance already running?
* 10310 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L1121) Unable to lock file: " + name + ". Is a mongod instance already running?
* 10332 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L111) Expected CurrentTime type
* 12596 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L1187) old lock file
* 13004 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L493) sent negative cursors to kill: 
* 13073 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L680) shutting down
* 13342 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L1205) Unable to truncate lock file
* 13511 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L750) document to insert can't have $ fields
* 13597 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L1197) can't start without --journal enabled when journal/ files are present
* 13618 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L1222) can't start without --journal enabled when journal/ files are present
* 13625 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L1201) Unable to truncate lock file
* 13627 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L1110) Unable to create/open lock file: " << name << ' ' << m << ". Is a mongod instance already running?
* 13658 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L492) bad kill cursors size: 
* 13659 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L491) sent 0 cursors to kill
* 16257 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L420) Invalid ns [" << ns << "]
* 16258 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/instance.cpp#L653) Invalid ns [" << ns << "]


src/mongo/db/jsobj.cpp
----
* 10060 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/jsobj.cpp#L541) woSortOrder needs a non-empty sortKey
* 10061 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/jsobj.cpp#L1148) type not supported for appendMinElementForType
* 10311 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/jsobj.cpp#L99) 
* 10312 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/jsobj.cpp#L257) 
* 12579 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/jsobj.cpp#L869) unhandled cases in BSONObj okForStorage
* 14853 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/jsobj.cpp#L1201) type not supported for appendMaxElementForType


src/mongo/db/json.cpp
----
* 10338 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/json.cpp#L233) Invalid use of reserved field name: 
* 10339 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/json.cpp#L406) Badly formatted bindata
* 10340 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/json.cpp#L642) Failure parsing JSON string near: 


src/mongo/db/lasterror.cpp
----
* 13649 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/lasterror.cpp#L93) no operation yet


src/mongo/db/lockstat.cpp
----
* 16146 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/lockstat.cpp#L76) 
* 16339 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/lockstat.cpp#L87) 


src/mongo/db/lockstate.cpp
----
* 16115 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/lockstate.cpp#L171) 
* 16169 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/lockstate.cpp#L84) 
* 16170 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/lockstate.cpp#L206) 
* 16231 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/lockstate.cpp#L201) 


src/mongo/db/matcher.cpp
----
* 10066 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L421) $where may only appear once in query
* 10067 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L422) $where query, but no script engine
* 10068 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L285) invalid operator: 
* 10069 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L371) BUG - can't operator for: 
* 10070 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L106) $where compile error
* 10071 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L120) 
* 10072 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L123) unknown error in invocation of $where function
* 10073 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L155) mod can't be 0
* 10341 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L90) code has to be set first!
* 10342 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L1315) pcre not compiled with utf8 support
* 12517 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L162) $elemMatch needs an Object
* 13020 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L215) with $all, can't mix $elemMatch and others
* 13029 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L362) can't use $not with $options, use BSON regex type instead
* 13030 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L479) $not cannot be empty
* 13031 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L489) invalid use of $not
* 13032 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L351) can't use $not with $regex, use BSON regex type instead
* 13086 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L377) $and/$or/$nor must be a nonempty array
* 13087 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L381) $and/$or/$nor match element must be an object
* 13089 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L423) no current client needed for $where
* 13276 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L310) $in needs an array
* 13277 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L321) $nin needs an array
* 13629 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L438) can't have undefined in a query expression
* 14844 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L516) $atomic specifier must be a top level field
* 15882 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L207) $elemMatch not allowed within $in
* 15902 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/matcher.cpp#L420) $where expression has an unexpected type


src/mongo/db/mongommf.cpp
----
* 13520 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/mongommf.cpp#L162) MongoMMF only supports filenames in a certain format 
* 13636 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/mongommf.cpp#L191) file " << filename() << " open/create failed in createPrivateMap (look in log for more information)
* 16112 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/mongommf.cpp#L46) 


src/mongo/db/namespace-inl.h
----
* 10080 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace-inl.h#L35) ns name too long, max size is 128
* 10348 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace-inl.h#L45) $extra: ns name too long


src/mongo/db/namespace_details-inl.h
----
* 10349 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details-inl.h#L55) E12000 idxNo fails
* 13283 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details-inl.h#L33) Missing Extra
* 14045 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details-inl.h#L34) missing Extra
* 14823 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details-inl.h#L41) missing extra
* 14824 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details-inl.h#L42) missing Extra


src/mongo/db/namespace_details.cpp
----
* 10079 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details.cpp#L171) bad .ns file length, cannot open database
* 10081 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details.cpp#L482) too many namespaces/collections
* 10082 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details.cpp#L497) allocExtra: too many namespaces/collections
* 10343 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details.cpp#L178) bad lenForNewNsFiles
* 10346 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details.cpp#L568) not implemented
* 10350 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details.cpp#L492) allocExtra: base ns missing?
* 10351 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespace_details.cpp#L493) allocExtra: extra already exists


src/mongo/db/namespacestring.h
----
* 10078 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespacestring.h#L142) nsToDatabase: ns too long
* 10088 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/namespacestring.h#L153) nsToDatabase: ns too long


src/mongo/db/nonce.cpp
----
* 10352 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/nonce.cpp#L33) Security is a singleton class
* 10353 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/nonce.cpp#L44) can't open dev/urandom: 
* 10354 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/nonce.cpp#L53) md5 unit test fails
* 10355 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/nonce.cpp#L62) devrandom failed


src/mongo/db/oplog.cpp
----
* 13044 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplog.cpp#L530) no ts field in query
* 13257 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplog.cpp#L349) 
* 13288 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplog.cpp#L54) replSet error write op to db before replSet initialized", str::startsWith(ns, "local.
* 13312 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplog.cpp#L145) replSet error : logOp() but not primary?
* 13347 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplog.cpp#L183) local.oplog.rs missing. did you drop it? if so restart server
* 13389 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplog.cpp#L73) local.oplog.rs missing. did you drop it? if so restart server
* 14038 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplog.cpp#L474) invalid _findingStartMode
* 14825 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplog.cpp#L853) error in applyOperation : unknown opType 
* 15916 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplog.cpp#L675) Can no longer connect to initial sync source: 
* 15917 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplog.cpp#L709) Got bad disk location when attempting to insert


src/mongo/db/oplogreader.h
----
* 15910 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplogreader.h#L83) Doesn't have cursor for reading oplog
* 15911 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/oplogreader.h#L88) Doesn't have cursor for reading oplog


src/mongo/db/ops/delete.cpp
----
* 10100 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/delete.cpp#L44) cannot delete from collection with reserved $ in name
* 10101 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/delete.cpp#L52) can't remove from a capped collection
* 12050 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/delete.cpp#L40) cannot delete from system namespace


src/mongo/db/ops/query.cpp
----
* 10110 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/query.cpp#L954) bad query object
* 13051 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/query.cpp#L993) tailable cursor requested on non capped collection
* 13052 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/query.cpp#L999) only {$natural:1} order allowed for tailable cursor
* 13530 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/query.cpp#L937) bad or malformed command request?
* 14833 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/query.cpp#L103) auth error
* 16256 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/query.cpp#L911) Invalid ns [" << ns << "]
* 16332 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/query.cpp#L900) can't have an empty ns


src/mongo/db/ops/query.h
----
* 16083 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/query.h#L46) reserve 16083


src/mongo/db/ops/update.cpp
----
* 10154 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update.cpp#L40) Modifiers and non-modifiers cannot be mixed
* 10155 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update.cpp#L476) cannot update reserved $ collection
* 10156 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update.cpp#L479) 
* 10157 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update.cpp#L308) multi-update requires all modified objects to have an _id
* 10158 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update.cpp#L425) multi update only works with $ operators
* 10159 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update.cpp#L453) multi update only works with $ operators
* 12522 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update.cpp#L45) $ operator made object too large


src/mongo/db/ops/update_internal.cpp
----
* 10131 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L116) $push can only be applied to an array
* 10132 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L187) $pushAll can only be applied to an array
* 10133 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L188) $pushAll has to be passed an array
* 10134 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L212) $pull/$pullAll can only be applied to an array
* 10135 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L245) $pop can only be applied to an array
* 10136 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L281) $bit needs an object
* 10137 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L282) $bit can only be applied to numbers
* 10138 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L283) $bit cannot update a value of type double
* 10139 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L291) $bit field must be number
* 10140 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L400) Cannot apply $inc modifier to non-number
* 10141 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L422) 
* 10142 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L430) 
* 10143 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L453) 
* 10145 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L701) 
* 10147 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L841) Invalid modifier specified: 
* 10148 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L858) 
* 10149 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L861) 
* 10150 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L864) 
* 10151 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L867) 
* 10152 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L870) 
* 10153 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L873) 
* 10399 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L745) ModSet::createNewFromMods - RIGHT_SUBFIELD should be impossible
* 10400 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L748) unhandled case
* 12591 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L461) 
* 12592 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L133) $addToSet can only be applied to an array
* 13478 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L604) can't apply mod in place - shouldn't have gotten here
* 13479 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L886) 
* 13480 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L889) 
* 13481 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L892) 
* 13482 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L895) 
* 13483 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L899) 
* 13484 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L903) 
* 13485 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L906) 
* 13486 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L909) 
* 13487 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L913) 
* 13488 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L916) 
* 13489 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L372) $rename source field invalid
* 13490 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L383) $rename target field invalid
* 13494 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L878) $rename target must be a string
* 13495 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L880) 
* 13496 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L883) 
* 15896 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L855) 
* 16069 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L723) ModSet::createNewFromMods - 
* 9016 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L307) unknown $bit operation: 
* 9017 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.cpp#L330) Mod::apply can't handle type: 


src/mongo/db/ops/update_internal.h
----
* 10161 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.h#L317) Invalid modifier specified 
* 12527 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.h#L212) not okForStorage
* 13492 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.h#L237) mod must be RENAME_TO type
* 9015 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ops/update_internal.h#L580) 


src/mongo/db/pdfile.cpp
----
* 10003 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1081) failing update: objects in a capped ns cannot grow
* 10083 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L258) create collection invalid size spec
* 10084 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L411) can't map file memory - mongo requires 64 bit build for larger datasets
* 10085 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L413) can't map file memory
* 10086 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L893) ns not found: 
* 10087 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L901) turn off profiling before dropping system.profile collection
* 10089 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1015) can't remove from a capped collection
* 10093 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1396) cannot insert into reserved $ collection
* 10094 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1397) invalid ns: 
* 10095 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1300) attempt to insert in reserved database name 'system'
* 10099 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1435) _id cannot be an array
* 10356 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L354) invalid ns: 
* 10357 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L515) shutdown in progress
* 10358 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L516) bad new extent size
* 10359 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L517) header==0 on new extent: 32 bit mmap space exceeded?
* 10360 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L664) Extent::reset bad magic value
* 10361 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L873) can't create .$freelist
* 12502 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L903) can't drop system ns
* 12503 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L941) 
* 12582 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1240) duplicate key insert for unique index of capped collection
* 12583 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1543) unexpected index insertion failure on capped collection
* 12586 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L111) cannot perform operation: a background operation is currently running for this database
* 12587 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L116) cannot perform operation: a background operation is currently running for this collection
* 13143 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1341) can't create index on system.indexes" , tabletoidxns.find( ".system.indexes
* 13440 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L394) 
* 13441 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L388) 
* 13596 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1076) cannot change _id of a document old:" << objOld << " new:
* 14037 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L234) can't create user databases on a --configsvr instance
* 14051 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1308) system.users entry needs 'user' field to be a string" , t["user
* 14052 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1309) system.users entry needs 'pwd' field to be a string" , t["pwd
* 14053 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1310) system.users entry needs 'user' field to be non-empty" , t["user
* 14054 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.cpp#L1311) system.users entry needs 'pwd' field to be non-empty" , t["pwd


src/mongo/db/pdfile.h
----
* 13640 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pdfile.h#L437) DataFileHeader looks corrupt at file open filelength:" << filelength << " fileno:


src/mongo/db/pipeline/accumulator.cpp
----
* 15943 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L28) group accumulator 
* 16030 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L59) reserved error
* 16031 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L60) reserved error
* 16032 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L61) reserved error
* 16033 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L62) reserved error
* 16036 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L64) reserved error
* 16037 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L65) reserved error
* 16038 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L66) reserved error
* 16039 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L67) reserved error
* 16040 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L68) reserved error
* 16041 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L69) reserved error
* 16042 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L70) reserved error
* 16043 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L71) reserved error
* 16044 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L72) reserved error
* 16045 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L73) reserved error
* 16046 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L74) reserved error
* 16047 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L75) reserved error
* 16048 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L76) reserved error
* 16049 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/accumulator.cpp#L77) reserved error


src/mongo/db/pipeline/doc_mem_monitor.cpp
----
* 15944 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/doc_mem_monitor.cpp#L55) terminating request:  request heap use exceeded 10% of physical RAM


src/mongo/db/pipeline/document.cpp
----
* 15945 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document.cpp#L114) cannot add undefined field 
* 15968 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document.cpp#L132) cannot set undefined field 


src/mongo/db/pipeline/document_source_filter.cpp
----
* 15946 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_filter.cpp#L75) a document filter expression must be an object


src/mongo/db/pipeline/document_source_group.cpp
----
* 15947 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_group.cpp#L148) a group's fields must be specified in an object
* 15948 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_group.cpp#L162) a group's _id may only be specified once
* 15949 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_group.cpp#L220) 
* 15950 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_group.cpp#L231) 
* 15951 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_group.cpp#L236) 
* 15952 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_group.cpp#L255) 
* 15953 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_group.cpp#L270) 
* 15954 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_group.cpp#L282) 
* 15955 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_group.cpp#L289) a group specification must include an _id


src/mongo/db/pipeline/document_source_limit.cpp
----
* 15957 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_limit.cpp#L94) the limit must be specified as a number
* 15958 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_limit.cpp#L101) the limit must be positive


src/mongo/db/pipeline/document_source_match.cpp
----
* 15959 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_match.cpp#L67) the match filter must be an expression in an object


src/mongo/db/pipeline/document_source_project.cpp
----
* 15960 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_project.cpp#L108) 
* 15961 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_project.cpp#L117) 
* 15969 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_project.cpp#L140) 
* 15970 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_project.cpp#L182) 
* 15971 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_project.cpp#L219) 
* 15984 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_project.cpp#L245) 


src/mongo/db/pipeline/document_source_skip.cpp
----
* 15956 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_skip.cpp#L119) 
* 15972 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_skip.cpp#L111) 


src/mongo/db/pipeline/document_source_sort.cpp
----
* 15973 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_sort.cpp#L117)  the 
* 15974 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_sort.cpp#L132) 
* 15975 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_sort.cpp#L137) 
* 15976 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_sort.cpp#L145) 


src/mongo/db/pipeline/document_source_unwind.cpp
----
* 15977 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_unwind.cpp#L108) 
* 15978 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_unwind.cpp#L121) 
* 15979 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_unwind.cpp#L214) 
* 15980 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_unwind.cpp#L218) the path of the field to unwind cannot be empty
* 15981 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/document_source_unwind.cpp#L231) the 


src/mongo/db/pipeline/expression.cpp
----
* 15982 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L58) 
* 15983 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L90) 
* 15990 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L101) this object is already an operator expression, and can't be used as a document expression (at \"
* 15991 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L145) 
* 15992 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L163) 
* 15993 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L2650) 
* 15994 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L801) 
* 15995 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L843) 
* 15996 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L2988) cannot subtract one date from another
* 15997 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L2657) 
* 15999 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L241) invalid operator \"
* 16000 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L412) can't add two dates together
* 16008 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L1343) 
* 16009 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L1349) 
* 16010 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L1356) 
* 16011 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L1371) 
* 16012 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L1384) 
* 16013 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L1396) 
* 16014 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L1640) 
* 16015 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L1654) 
* 16019 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L252) the 
* 16020 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L275) the 
* 16021 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L259) the 
* 16022 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L289) the 
* 16023 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L2032) 
* 16024 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L2070) 
* 16025 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L2110) 
* 16026 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L2117) 
* 16027 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L2080) 
* 16034 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L2931) 
* 16035 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/expression.cpp#L2937) 


src/mongo/db/pipeline/field_path.cpp
----
* 15998 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/field_path.cpp#L53) 


src/mongo/db/pipeline/value.cpp
----
* 16001 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/value.cpp#L86) 
* 16002 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/value.cpp#L180) 
* 16003 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/value.cpp#L543) 
* 16004 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/value.cpp#L569) 
* 16005 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/value.cpp#L595) 
* 16006 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/value.cpp#L615) 
* 16007 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/value.cpp#L651) 
* 16016 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/value.cpp#L739) 
* 16017 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/value.cpp#L790) 
* 16018 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/pipeline/value.cpp#L893) 


src/mongo/db/projection.cpp
----
* 10053 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L100) You cannot currently mix including and excluding fields. 
* 10371 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L26) can only add to Projection once
* 13097 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L83) Unsupported projection option: 
* 13098 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L61) $slice only supports numbers and [skip, limit] arrays
* 13099 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L51) $slice array wrong size
* 13100 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L56) $slice limit must be positive
* 16342 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L66) elemMatch: invalid argument.  object required.
* 16343 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L68) Cannot specify positional operator and $elemMatch
* 16344 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L71) Cannot use $elemMatch projection on a nested field
* 16345 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L107) Cannot exclude array elements with the positional operator
* 16346 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L109) Cannot specify more than one positional array element per query
* 16347 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L111) Cannot specify positional operator and $elemMatch
* 16348 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L174) matchers are only supported for $elemMatch
* 16349 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L184) $elemMatch specified, but projection field not found.
* 16350 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L188) $elemMatch called on document element with eoo
* 16351 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L190) $elemMatch called on array element with eoo
* 16352 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L287) positional operator (
* 16353 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L292) positional operator element mismatch
* 16354 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/projection.cpp#L343) Positional operator does not match the query specifier.


src/mongo/db/queryoptimizer.cpp
----
* 10111 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L357) table scans not allowed:
* 10112 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L73) bad hint
* 10113 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L85) bad hint
* 10363 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L292) newCursor() with start location not implemented for indexed plans
* 10364 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L315) newReverseCursor() not implemented for indexed plans
* 10365 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L742) 
* 10366 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L623) natural order cannot be specified with $min/$max
* 10367 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L635) 
* 10368 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L696) Unable to locate previously recorded index
* 10369 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L1018) no plans
* 13038 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L659) can't find special index: 
* 13040 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L160) no type for special: 
* 13268 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L1218) invalid $or spec
* 13292 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L60) hint eoo
* 16330 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L654) 'special' query operator not allowed
* 16331 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.cpp#L750) 'special' plan hint not allowed


src/mongo/db/queryoptimizer.h
----
* 13266 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.h#L614) not implemented for $or query
* 13271 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizer.h#L617) no more clauses


src/mongo/db/queryoptimizercursorimpl.cpp
----
* 14809 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizercursorimpl.cpp#L666) Invalid access for cursor that is not ok()
* 16249 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizercursorimpl.cpp#L99) 
* 9011 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryoptimizercursorimpl.cpp#L82) 


src/mongo/db/queryutil-inl.h
----
* 14049 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil-inl.h#L138) FieldRangeSetPair invalid index specified


src/mongo/db/queryutil.cpp
----
* 10370 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L364) $all requires array
* 12580 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L174) invalid query
* 13033 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L764) can't have 2 special fields
* 13034 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L902) invalid use of $not
* 13041 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L912) invalid use of $not
* 13050 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L876) $all requires array
* 13262 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L1701) $or requires nonempty array
* 13263 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L1705) $or array must contain objects
* 13274 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L1717) no or clause to pop
* 13291 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L1707) $or may not contain 'special' query
* 13303 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L1232) combinatorial limit of $in partitioning of result set exceeded
* 13304 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L1242) combinatorial limit of $in partitioning of result set exceeded
* 13385 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L1104) combinatorial limit of $in partitioning of result set exceeded
* 13454 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L255) invalid regular expression operator
* 14048 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L1336) FieldRangeSetPair invalid index specified
* 14816 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L957) $and expression must be a nonempty array
* 14817 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L963) $and elements must be objects
* 15881 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.cpp#L178) $elemMatch not allowed within $in


src/mongo/db/queryutil.h
----
* 10102 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.h#L41) bad order array
* 10103 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.h#L42) bad order array [2]
* 10104 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.h#L45) too many ordering elements
* 10105 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.h#L129) bad skip value in query
* 12001 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.h#L210) E12001 can't sort with $snapshot
* 12002 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.h#L211) E12002 can't use hint with $snapshot
* 13513 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/queryutil.h#L180) sort must be an object or array


src/mongo/db/record.cpp
----
* 16236 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/record.cpp#L323) 


src/mongo/db/repl.cpp
----
* 10002 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L398) local.sources collection corrupt?
* 10118 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L266) 'host' field not set in sources collection object
* 10119 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L267) only source='main' allowed for now with replication", sourceName() == "main
* 10120 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L270) bad sources 'syncedTo' field value
* 10123 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L1012) replication error last applied optime at slave >= nextOpTime from master
* 10124 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L1248) 
* 10384 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L409) --only requires use of --source
* 10385 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L465) Unable to get database list
* 10386 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L781) non Date ts found: 
* 10389 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L810) Unable to get database list
* 10390 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L900) got $err reading remote oplog
* 10391 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L905) repl: bad object read from remote oplog
* 10392 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L1080) bad user object? [1]
* 10393 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L1081) bad user object? [2]
* 13344 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L896) trying to slave off of a non-master
* 13435 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L1556) not master and slaveOk=false
* 13436 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L1558) 
* 14032 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L570) Invalid 'ts' in remote log
* 14033 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L576) Unable to get database list
* 14034 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L618) Duplicate database names present after attempting to delete duplicates
* 15914 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl.cpp#L629) Failure retrying initial sync update


src/mongo/db/repl/bgsync.cpp
----
* 1000 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/bgsync.cpp#L277) replSet source for syncing doesn't seem to be await capable -- is it an older version of mongodb?
* 16235 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/bgsync.cpp#L519) going to start syncing, but buffer is not empty


src/mongo/db/repl/health.h
----
* 13112 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/health.h#L41) bad replset heartbeat option
* 13113 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/health.h#L42) bad replset heartbeat option


src/mongo/db/repl/heartbeat.cpp
----
* 15900 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/heartbeat.cpp#L150) can't heartbeat: too much lock


src/mongo/db/repl/rs.cpp
----
* 13093 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs.cpp#L319) bad --replSet config string format is: <setname>[/<seedhost1>,<seedhost2>,...]
* 13096 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs.cpp#L338) bad --replSet command line config string - dups?
* 13101 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs.cpp#L340) can't use localhost in replset host list
* 13114 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs.cpp#L336) bad --replSet seed hostname
* 13290 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs.cpp#L417) bad replSet oplog entry?
* 13302 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs.cpp#L521) replSet error self appears twice in the repl set configuration


src/mongo/db/repl/rs_config.cpp
----
* 13107 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L532) 
* 13108 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L542) bad replset config -- duplicate hosts in the config object?
* 13109 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L648) multiple rows in " << rsConfigNs << " not supported host: 
* 13115 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L463) bad " + rsConfigNs + " config: version
* 13117 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L549) bad " + rsConfigNs + " config
* 13122 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L566) bad repl set config?
* 13126 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L140) bad Member config
* 13131 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L473) replSet error parsing (or missing) 'members' field in config object
* 13132 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L320) 
* 13133 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L324) replSet bad config no members
* 13135 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L538) 
* 13260 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L623) 
* 13308 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L323) replSet bad config version #
* 13309 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L325) replSet bad config maximum number of members is 12
* 13393 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L548) can't use localhost in repl set member names except when using it for all members
* 13419 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L147) priorities must be between 0.0 and 100.0
* 13432 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L272) _id may not change for members
* 13433 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L289) can't find self in new replset config
* 13434 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L43) unexpected field '" << e.fieldName() << "' in object
* 13437 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L148) slaveDelay requires priority be zero
* 13438 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L149) bad slaveDelay value
* 13439 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L150) priority must be 0 when hidden=true
* 13476 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L276) buildIndexes may not change for members
* 13477 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L151) priority must be 0 when buildIndexes=false
* 13510 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L282) arbiterOnly may not change for members
* 13612 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L332) replSet bad config maximum number of voting members is 7
* 13613 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L333) replSet bad config no voting members
* 13645 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L266) hosts cannot switch between localhost and hostname
* 14046 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L382) getLastErrorMode rules must be objects
* 14827 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L524) arbiters cannot have tags
* 14828 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L394) getLastErrorMode criteria must be greater than 0: 
* 14829 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L389) getLastErrorMode criteria must be numeric
* 14831 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_config.cpp#L399) mode " << clauseObj << " requires 


src/mongo/db/repl/rs_initialsync.cpp
----
* 13404 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initialsync.cpp#L44) 
* 16233 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initialsync.cpp#L66) 


src/mongo/db/repl/rs_initiate.cpp
----
* 13144 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initiate.cpp#L130) 
* 13145 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initiate.cpp#L93) set name does not match the set name host " + i->h.toString() + " expects
* 13256 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initiate.cpp#L97) member " + i->h.toString() + " is already initiated
* 13259 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initiate.cpp#L83) 
* 13278 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initiate.cpp#L58) bad config: isSelf is true for multiple hosts: 
* 13279 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initiate.cpp#L64) 
* 13311 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initiate.cpp#L136) member " + i->h.toString() + " has data already, cannot initiate set.  All members except initiator must be empty.
* 13341 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initiate.cpp#L102) member " + i->h.toString() + " has a config version >= to the new cfg version; cannot change config
* 13420 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_initiate.cpp#L51) initiation and reconfiguration of a replica set must be sent to a node that can become primary


src/mongo/db/repl/rs_rollback.cpp
----
* 13410 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_rollback.cpp#L344) replSet too much data to roll back
* 13423 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_rollback.cpp#L454) replSet error in rollback can't find 
* 15909 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_rollback.cpp#L397) replSet rollback error resyncing collection 


src/mongo/db/repl/rs_sync.cpp
----
* 12000 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_sync.cpp#L421) rs slaveDelay differential too big check clocks and systems
* 15915 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_sync.cpp#L130) 
* 16113 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_sync.cpp#L595) 
* 16359 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_sync.cpp#L112) 
* 16360 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_sync.cpp#L116) 
* 16361 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl/rs_sync.cpp#L143) 


src/mongo/db/repl_block.cpp
----
* 14830 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl_block.cpp#L162) unrecognized getLastError mode: 
* 16250 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/repl_block.cpp#L148) w has to be a string or a number


src/mongo/db/replutil.h
----
* 10107 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/replutil.h#L82) not master


src/mongo/db/restapi.cpp
----
* 13085 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/restapi.cpp#L150) query failed for dbwebserver
* 16172 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/restapi.cpp#L241) couldn't get readlock to open admin db
* 16173 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/restapi.cpp#L254) couldn't get read lock to get admin auth credentials
* 16174 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/restapi.cpp#L263) couldn't get read lock to check admin user


src/mongo/db/scanandorder.cpp
----
* 15925 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/scanandorder.cpp#L39) cannot sort with keys that are parallel arrays
* 16355 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/scanandorder.cpp#L78) positional operator specified, but no array match


src/mongo/db/security.cpp
----
* 15889 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/security.cpp#L119) key file must be used to log in with internal user
* 16232 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/security.cpp#L35) 


src/mongo/db/ttl.cpp
----
* 16230 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/db/ttl.cpp#L63) key for ttl index can only have 1 field


src/mongo/dbtests/jsobjtests.cpp
----
* 12528 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/dbtests/jsobjtests.cpp#L1979) should be ok for storage:
* 12529 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/dbtests/jsobjtests.cpp#L1986) should NOT be ok for storage:


src/mongo/s/balance.cpp
----
* 13258 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/balance.cpp#L334) oids broken after resetting!
* 16356 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/balance.cpp#L236) tag ranges not valid for: 


src/mongo/s/chunk.cpp
----
* 10163 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L127) can only handle numbers here - which i think is correct
* 10165 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L265) can't split as shard doesn't have a manager
* 10167 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L303) can't move shard to its current location!
* 10169 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L448) datasize failed!" , conn->get()->runCommand( "admin
* 10170 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L69) Chunk needs a ns
* 10171 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L72) Chunk needs a server
* 10172 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L74) Chunk needs a min
* 10173 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L75) Chunk needs a max
* 10174 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1193) config servers not all up
* 10412 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L420) 
* 13003 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L268) can't split a chunk with only one distinct value
* 13141 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1050) Chunk map pointed to incorrect chunk
* 13282 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L670) Couldn't load a valid config for " + _ns + " after 3 attempts. Please try again.
* 13327 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L70) Chunk ns must match server ns
* 13331 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1191) collection's metadata is undergoing changes. Please try again.
* 13332 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L266) need a split key to split chunk
* 13333 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L267) can't split a chunk in that many parts
* 13345 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L190) 
* 13405 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1130) min value " << min << " does not have shard key
* 13406 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1131) max value " << max << " does not have shard key
* 13449 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L991) collection " << _ns << " already sharded with 
* 13501 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1076) use geoNear command rather than $near query
* 13502 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1083) unrecognized special query type: 
* 13503 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L160) 
* 13507 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1137) no chunks found between bounds " << min << " and 
* 14022 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1188) Error locking distributed lock for chunk drop.
* 15903 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1017) 
* 16068 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1122) no chunk ranges available
* 16338 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1228) 
* 8070 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1054) 
* 8071 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/chunk.cpp#L1250) cleaning up after drop failed: 


src/mongo/s/client_info.cpp
----
* 13134 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/client_info.cpp#L60) 


src/mongo/s/commands_public.cpp
----
* 10420 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L810) how could chunk manager be null!
* 12594 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L543) how could chunk manager be null!
* 13002 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L668) shard internal error chunk manager should never be null
* 13091 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L875) how could chunk manager be null!
* 13137 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L408) Source and destination collections must be on same shard
* 13138 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L402) You can't rename a sharded collection
* 13139 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L403) You can't rename to a sharded collection
* 13140 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L401) Don't recognize source or target DB
* 13343 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L671) query for sharded findAndModify must have shardkey
* 13398 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L422) cant copy to sharded DB
* 13399 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L430) need a fromdb argument
* 13400 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L433) don't know where source DB is
* 13401 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L434) cant copy from sharded DB
* 13402 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L419) need a todb argument
* 13407 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L711) how could chunk manager be null!
* 13408 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L717) keyPattern must equal shard key
* 13500 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L980) how could chunk manager be null!
* 15920 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L1178) Cannot output to a non-sharded collection, a sharded collection exists
* 16246 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L939) Shard " + conf->getName() + " is too old to support GridFS sharded by {files_id:1, n:1}
* 16260 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/commands_public.cpp#L482) skip has to be positive


src/mongo/s/config.cpp
----
* 10178 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L147) no primary!
* 10181 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L310) not sharded:
* 10184 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L677) _dropShardedCollections too many collections - bailing
* 10187 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L722) need configdbs
* 10189 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L893) should only have 1 thing in config.version
* 13396 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L521) DBConfig save failed: 
* 13473 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L110) failed to save collection (" + ns + "): 
* 13509 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L454) can't migrate from 1.5.x release to the current one; need to upgrade to 1.6.x first
* 13648 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L167) can't shard collection because not all config servers are up
* 14822 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L394) state changed in the middle: 
* 15883 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L426) not sharded after chunk manager reset : 
* 15885 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L341) not sharded after reloading from chunks : 
* 8042 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L166) db doesn't have sharding enabled
* 8043 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.cpp#L175) collection already sharded


src/mongo/s/config.h
----
* 10190 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.h#L220) ConfigServer not setup
* 8041 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/config.h#L163) no primary shard configured for db: 


src/mongo/s/cursors.cpp
----
* 10191 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/cursors.cpp#L91) cursor already done
* 13286 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/cursors.cpp#L239) sent 0 cursors to kill
* 13287 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/cursors.cpp#L240) too many cursors to kill


src/mongo/s/d_chunk_manager.cpp
----
* 13542 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L183) collection doesn't have a key: 
* 13585 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L344) version " << version.toString() << " not greater than 
* 13586 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L312) couldn't find chunk " << min << "->
* 13587 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L320) 
* 13588 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L380) 
* 13590 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L334) setting version to " << version.toString() << " on removing last chunk
* 13591 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L366) version can't be set to zero
* 14039 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L407) version " << version.toString() << " not greater than 
* 14040 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L414) can split " << min << " -> " << max << " on 
* 16181 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L128) could not initialize cursor to config server chunks collection for ns 
* 16229 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_chunk_manager.cpp#L161) 


src/mongo/s/d_logic.cpp
----
* 10422 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_logic.cpp#L111) write with bad shard config and no server id!
* 9517 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_logic.cpp#L104) writeback


src/mongo/s/d_split.cpp
----
* 13593 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_split.cpp#L717) 


src/mongo/s/d_state.cpp
----
* 13298 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_state.cpp#L79) 
* 13299 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_state.cpp#L101) 
* 13647 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/d_state.cpp#L592) context should be empty here, is: 


src/mongo/s/grid.cpp
----
* 10185 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/grid.cpp#L118) can't find a shard to put new db on
* 10186 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/grid.cpp#L138) removeDB expects db name
* 10421 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/grid.cpp#L540) 
* 15918 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/grid.cpp#L44) 


src/mongo/s/request.cpp
----
* 10194 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/request.cpp#L109) can't call primaryShard on a sharded collection!
* 13644 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/request.cpp#L80) can't use 'local' database through mongos" , ! str::startsWith( getns() , "local.
* 15845 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/request.cpp#L62) 
* 8060 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/request.cpp#L105) can't call primaryShard on a sharded collection


src/mongo/s/security.cpp
----
* 15890 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/security.cpp#L35) key file must be used to log in with internal user


src/mongo/s/server.cpp
----
* 10197 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/server.cpp#L192) createDirectClient not implemented for sharding yet
* 15849 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/server.cpp#L97) client info not defined


src/mongo/s/shard.cpp
----
* 13128 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard.cpp#L135) can't find shard for: 
* 13129 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard.cpp#L117) can't find shard for: 
* 13136 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard.cpp#L336) 
* 13632 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard.cpp#L44) couldn't get updated shard list from config server
* 15847 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard.cpp#L393) can't authenticate to shard server
* 15907 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard.cpp#L410) could not initialize sharding on connection 


src/mongo/s/shard_version.cpp
----
* 10428 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard_version.cpp#L246) need_authoritative set but in authoritative mode already
* 10429 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard_version.cpp#L279) 
* 15904 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard_version.cpp#L79) cannot set version on invalid connection 
* 15905 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard_version.cpp#L84) cannot set version or shard on pair connection 
* 15906 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard_version.cpp#L87) cannot set version or shard on sync connection 
* 16334 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shard_version.cpp#L90) cannot set version or shard on custom connection 


src/mongo/s/shardkey.cpp
----
* 10198 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shardkey.cpp#L47) left object ("  << lObject << ") doesn't have full shard key (
* 10199 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shardkey.cpp#L50) right object (" << rObject << ") doesn't have full shard key (


src/mongo/s/shardkey.h
----
* 13334 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/shardkey.h#L125) Shard Key must be less than 512 bytes


src/mongo/s/strategy.cpp
----
* 10200 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy.cpp#L72) mongos: error calling db


src/mongo/s/strategy_shard.cpp
----
* 10201 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L733) invalid update
* 10203 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L889) bad delete message
* 10204 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L180) dbgrid: getmore: error calling db
* 10205 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L998) can't use unique indexes with sharding  ns:
* 12376 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L632) 
* 13123 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L576) Can't modify shard key's value. field: 
* 13505 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L863) 
* 13506 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L718) 
* 16055 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L414) too many retries during bulk insert, " << insertsRemaining.size() << " inserts remaining
* 16056 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L415) shutting down server during bulk insert, " << insertsRemaining.size() << " inserts remaining
* 16064 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L568) 
* 16065 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L619) multi-updates require $ops rather than replacement object
* 16336 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L167) 
* 8010 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L54) something is wrong, shouldn't see a command here
* 8011 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L350) 
* 8012 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L691) 
* 8013 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L607) 
* 8014 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L655) cannot modify shard key for collection 
* 8015 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L877) 
* 8016 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L981) can't do this write op on sharded collection
* 8050 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L1019) can't update system.indexes
* 8051 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L1022) can't delete indexes on sharded collection yet
* 8052 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_shard.cpp#L1026) handleIndexWrite invalid write op


src/mongo/s/strategy_single.cpp
----
* 13390 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/strategy_single.cpp#L92) unrecognized command: 


src/mongo/s/writeback_listener.cpp
----
* 10427 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/writeback_listener.cpp#L168) invalid writeback message
* 13403 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/writeback_listener.cpp#L110) didn't get writeback for: " << oid << " after: " << t.millis() << " ms
* 13641 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/writeback_listener.cpp#L69) can't parse host [" << conn.getServerAddress() << "]
* 14041 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/writeback_listener.cpp#L100) got writeback waitfor for older id 
* 15884 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/s/writeback_listener.cpp#L312) 


src/mongo/scripting/bench.cpp
----
* 14811 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/bench.cpp#L308) invalid bench dynamic piece: 
* 15931 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/bench.cpp#L387) Authenticating to connection for _benchThread failed: 
* 15932 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/bench.cpp#L674) Authenticating to connection for benchThread failed: 
* 16147 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/bench.cpp#L223) Already finished.
* 16152 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/bench.cpp#L233) Cannot wait for state 
* 16157 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/bench.cpp#L200) 
* 16158 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/bench.cpp#L202) 
* 16164 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/bench.cpp#L168) loopCommands config not supported", args["loopCommands


src/mongo/scripting/engine.cpp
----
* 10206 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine.cpp#L85) 
* 10207 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine.cpp#L92) compile failed
* 10208 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine.cpp#L178) need to have locallyConnected already
* 10209 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine.cpp#L199) name has to be a string: 
* 10210 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine.cpp#L200) value has to be set
* 10430 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine.cpp#L170) invalid object id: not hex
* 10448 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine.cpp#L161) invalid object id: length


src/mongo/scripting/engine.h
----
* 13474 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine.h#L202) no _getInterruptSpecCallback
* 9004 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine.h#L92) invoke failed: 
* 9005 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine.h#L101) invoke failed: 


src/mongo/scripting/engine_spidermonkey.cpp
----
* 10212 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L81) holder magic value is wrong
* 10214 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L230) not a number
* 10215 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L318) not an object
* 10216 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L327) not a function
* 10217 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L384) can't append field.  name:" + name + " type: 
* 10218 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L718) not done: toval
* 10219 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L745) object passed to getPropery is null
* 10220 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L845) don't know what to do with this op
* 10221 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1374) JS_NewRuntime failed
* 10223 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1457) deleted SMScope twice?
* 10224 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1503) already local connected
* 10225 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1513) already setup for external db
* 10226 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1515) connected to different db
* 10227 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1584) unknown type
* 10228 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1755)  exec failed: 
* 10431 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1433) JS_NewContext failed
* 10432 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1440) JS_NewObject failed for global
* 10433 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1442) js init failed
* 13072 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L40) JS_NewObject failed: 
* 13076 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L151) recursive toObject
* 13615 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L44) JS allocation failed, either memory leak or using too much memory
* 16268 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L201) error converting UTF-16 string to UTF-8
* 16269 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L306) 
* 16270 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L526) conversion from string to JavaScript value failed
* 16271 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L799) 
* 16272 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L856) 
* 16273 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L880) 
* 16274 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L931) 
* 16275 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L956) 
* 16276 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L978) 
* 16277 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1082) 
* 16278 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1113) 
* 16279 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1144) 
* 16280 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1172) 
* 16281 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1221) 
* 16282 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1284) 
* 16283 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1306) 
* 16284 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1357) 
* 16285 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1788) 
* 16286 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1817) 
* 16287 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_spidermonkey.cpp#L1968) 


src/mongo/scripting/engine_v8.cpp
----
* 10230 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_v8.cpp#L646) can't handle external yet
* 10231 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_v8.cpp#L691) not an object
* 10232 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_v8.cpp#L753) not a func
* 10233 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_v8.cpp#L863) 
* 10234 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_v8.cpp#L890) 
* 12509 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_v8.cpp#L654) don't know what this is: 
* 12510 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_v8.cpp#L955) externalSetup already called, can't call externalSetup
* 12511 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_v8.cpp#L959) localConnect called with a different name previously
* 12512 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_v8.cpp#L978) localConnect already called, can't call externalSetup
* 13475 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/engine_v8.cpp#L873) 


src/mongo/scripting/sm_db.cpp
----
* 10235 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L75) no cursor!
* 10236 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L81) no args to internal_cursor_constructor
* 10239 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L279) no connection!
* 10245 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L416) no connection!
* 10248 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L456) no connection!
* 10251 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L518) no connection!
* 16288 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L92) 
* 16289 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L112) 
* 16290 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L129) 
* 16291 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L148) 
* 16292 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L173) 
* 16293 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L219) 
* 16294 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L257) 
* 16295 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L272) 
* 16296 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L298) 
* 16297 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L349) 
* 16298 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L398) 
* 16299 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L439) 
* 16300 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L501) 
* 16301 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L542) 
* 16302 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L580) 
* 16303 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L625) 
* 16304 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L692) 
* 16305 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L731) 
* 16306 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L779) 
* 16307 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L820) 
* 16308 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L865) 
* 16309 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L988) 
* 16310 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1016) 
* 16311 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1041) 
* 16312 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1072) 
* 16313 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1092) 
* 16314 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1137) 
* 16315 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1160) 
* 16316 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1216) 
* 16317 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1268) 
* 16318 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1286) 
* 16319 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1318) 
* 16320 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1377) 
* 16321 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1395) 
* 16322 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1419) 
* 16323 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1503) 
* 16324 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/sm_db.cpp#L1530) 


src/mongo/scripting/utils.cpp
----
* 10261 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/utils.cpp#L27) 
* 16259 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/scripting/utils.cpp#L49) 


src/mongo/shell/shell_utils.cpp
----
* 10258 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils.cpp#L80) processinfo not supported
* 12513 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils.cpp#L151) connect failed", scope.exec( _dbConnect , "(connect)
* 12514 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils.cpp#L154) login failed", scope.exec( _dbAuth , "(auth)
* 12518 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils.cpp#L97) srand requires a single numeric argument
* 12519 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils.cpp#L108) rand accepts no arguments
* 12597 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils.cpp#L55) need to specify 1 argument
* 13006 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils.cpp#L119) isWindows accepts no arguments


src/mongo/shell/shell_utils_extended.cpp
----
* 10257 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils_extended.cpp#L45) need to specify 1 argument to listFiles
* 12581 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils_extended.cpp#L54) 
* 13301 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils_extended.cpp#L138) cat() : file to big to load as a variable
* 13411 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils_extended.cpp#L204) getHostName accepts no arguments
* 13619 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils_extended.cpp#L189) fuzzFile takes 2 arguments
* 13620 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils_extended.cpp#L192) couldn't open file to fuzz


src/mongo/shell/shell_utils_launcher.cpp
----
* 14042 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils_launcher.cpp#L366) 
* 15852 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils_launcher.cpp#L702) stopMongoByPid needs a number
* 15853 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/shell/shell_utils_launcher.cpp#L693) stopMongo needs a number


src/mongo/tools/docgenerator.cpp
----
* 16261 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/docgenerator.cpp#L27) blob is not a string", (args["blob
* 16262 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/docgenerator.cpp#L30) md5 seed is not a string", (args["md5seed
* 16263 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/docgenerator.cpp#L33) counterUp is not a number", args["counterUp
* 16264 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/docgenerator.cpp#L36) counterDown is not a number", args["counterDown


src/mongo/tools/dump.cpp
----
* 10262 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/dump.cpp#L124) couldn't open file
* 14035 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/dump.cpp#L78) couldn't write to file
* 15933 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/dump.cpp#L139) Couldn't open file: 


src/mongo/tools/import.cpp
----
* 10263 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/import.cpp#L125) unknown error reading file
* 13289 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/import.cpp#L135) Invalid UTF8 character detected
* 13293 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/import.cpp#L156) BSON representation of supplied JSON array is too large: 
* 13295 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/import.cpp#L116) JSONArray file too large
* 13504 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/import.cpp#L190) BSON representation of supplied JSON is too large: 
* 15854 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/import.cpp#L217) CSV file ends while inside quoted field
* 16329 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/import.cpp#L121) read error, or input line too long (max length: 


src/mongo/tools/loadgenerator.cpp
----
* 16265 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/loadgenerator.cpp#L111) 
* 16266 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/loadgenerator.cpp#L113) 
* 16267 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/loadgenerator.cpp#L130) 


src/mongo/tools/restore.cpp
----
* 15934 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/restore.cpp#L389) JSON object size didn't match file size
* 15935 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/restore.cpp#L83) user does not have write access
* 15936 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/restore.cpp#L453) Creating collection " + _curns + " failed. Errmsg: " + info["errmsg


src/mongo/tools/sniffer.cpp
----
* 10266 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/sniffer.cpp#L480) can't use --source twice
* 10267 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/sniffer.cpp#L481) source needs more args


src/mongo/tools/tool.cpp
----
* 10264 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/tool.cpp#L496) invalid object size: 
* 10265 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/tool.cpp#L532) counts don't match
* 9997 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/tool.cpp#L435) authentication failed: 
* 9998 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/tool.cpp#L398) you need to specify fields
* 9999 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/tools/tool.cpp#L377) file: " + fn ) + " doesn't exist


src/mongo/unittest/unittest.cpp
----
* 10162 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/unittest/unittest.cpp#L225) 
* 16145 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/unittest/unittest.cpp#L188) 


src/mongo/util/alignedbuilder.cpp
----
* 13524 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/alignedbuilder.cpp#L109) out of memory AlignedBuilder
* 13584 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/alignedbuilder.cpp#L27) out of memory AlignedBuilder


src/mongo/util/assert_util.h
----
* 10437 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/assert_util.h#L240) unknown exception
* 123 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/assert_util.h#L72) blah
* 13294 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/assert_util.h#L238) 
* 14043 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/assert_util.h#L249) 
* 14044 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/assert_util.h#L251) unknown exception
* 16199 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/assert_util.h#L200) 


src/mongo/util/background.cpp
----
* 13643 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/background.cpp#L55) backgroundjob already started: 


src/mongo/util/base64.cpp
----
* 10270 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/base64.cpp#L79) invalid base64


src/mongo/util/concurrency/list.h
----
* 14050 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/list.h#L84) List1: item to orphan not in list


src/mongo/util/concurrency/qlock.h
----
* 16137 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L319) 
* 16138 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L325) 
* 16139 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L336) 
* 16140 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L343) 
* 16200 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L116) 
* 16201 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L122) 
* 16202 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L207) 
* 16203 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L218) 
* 16204 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L219) 
* 16205 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L220) 
* 16206 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L238) 
* 16207 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L239) 
* 16208 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L240) 
* 16209 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L251) 
* 16210 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L252) 
* 16211 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L253) 
* 16212 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L263) 
* 16214 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L274) 
* 16215 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L275) 
* 16216 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L284) 
* 16217 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L285) 
* 16219 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L292) 
* 16220 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L293) 
* 16221 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L294) 
* 16222 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/concurrency/qlock.h#L295) 


src/mongo/util/file.h
----
* 10438 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/file.h#L117) ReadFile error - truncated file?


src/mongo/util/file_allocator.cpp
----
* 10439 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/file_allocator.cpp#L294) 
* 10440 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/file_allocator.cpp#L178) 
* 10441 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/file_allocator.cpp#L182) Unable to allocate new file of size 
* 10442 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/file_allocator.cpp#L184) Unable to allocate new file of size 
* 10443 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/file_allocator.cpp#L199) FileAllocator: file write failed
* 13653 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/file_allocator.cpp#L316) 
* 16062 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/file_allocator.cpp#L142) fstatfs failed: 
* 16063 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/file_allocator.cpp#L160) ftruncate failed: 


src/mongo/util/hook_win32.cpp
----
* 16239 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/hook_win32.cpp#L86) 
* 16240 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/hook_win32.cpp#L92) 


src/mongo/util/log.cpp
----
* 10268 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/log.cpp#L72) LoggingManager already started
* 14036 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/log.cpp#L112) couldn't write to log file


src/mongo/util/logfile.cpp
----
* 13514 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L251) 
* 13515 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L237) 
* 13516 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L175) couldn't open file " << name << " for writing 
* 13517 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L127) error appending to file 
* 13518 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L71) couldn't open file " << name << " for writing 
* 13519 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L125) error 87 appending to file - invalid parameter
* 15871 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L85) Couldn't truncate file: 
* 15873 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L193) Couldn't truncate file: 
* 16142 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L224) 
* 16143 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L225) 
* 16144 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/logfile.cpp#L223) 


src/mongo/util/mmap.cpp
----
* 13468 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap.cpp#L48) can't create file already exists 
* 13617 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap.cpp#L200) MongoFile : multiple opens of same filename
* 15922 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap.cpp#L72) couldn't get file length when opening mapping 
* 15923 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap.cpp#L82) couldn't get file length when opening mapping 
* 16325 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap.cpp#L35) 
* 16326 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap.cpp#L36) 
* 16327 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap.cpp#L38) 


src/mongo/util/mmap_posix.cpp
----
* 10446 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap_posix.cpp#L100) mmap: can't map area of size 0 file: 
* 10447 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap_posix.cpp#L110) map file alloc failed, wanted: " << length << " filelen: 


src/mongo/util/mmap_win.cpp
----
* 13056 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap_win.cpp#L401) Async flushing not supported on windows
* 16148 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap_win.cpp#L339) 
* 16165 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap_win.cpp#L129) 
* 16166 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap_win.cpp#L221) 
* 16167 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap_win.cpp#L300) 
* 16168 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap_win.cpp#L322) 
* 16225 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap_win.cpp#L198) 
* 16362 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/mmap_win.cpp#L276) 


src/mongo/util/net/hostandport.h
----
* 13095 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/hostandport.h#L213) HostAndPort: bad port #
* 13110 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/hostandport.h#L207) HostAndPort: host is empty


src/mongo/util/net/httpclient.cpp
----
* 10271 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/httpclient.cpp#L47) invalid url" , url.find( "http://
* 15862 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/httpclient.cpp#L108) no ssl support


src/mongo/util/net/listen.cpp
----
* 15863 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/listen.cpp#L134) listen(): invalid socket? 


src/mongo/util/net/message.h
----
* 13273 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/message.h#L169) single data buffer expected
* 16141 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/message.h#L58) cannot translate opcode 


src/mongo/util/net/message_port.cpp
----
* 15901 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/message_port.cpp#L249) client disconnected during operation


src/mongo/util/net/message_server_asio.cpp
----
* 10273 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/message_server_asio.cpp#L110) _cur not empty! pipelining requests not supported
* 10274 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/message_server_asio.cpp#L171) pipelining requests doesn't work yet


src/mongo/util/net/message_server_port.cpp
----
* 10275 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/message_server_port.cpp#L116) multiple PortMessageServer not supported


src/mongo/util/net/sock.cpp
----
* 13079 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/sock.cpp#L165) path to unix socket too long
* 13080 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/sock.cpp#L163) no unix socket support on windows
* 13082 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/sock.cpp#L251) getnameinfo error 
* 15861 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/sock.cpp#L496) can't create SSL
* 15864 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/sock.cpp#L454) can't create SSL Context: 
* 15865 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/sock.cpp#L462) 
* 15866 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/sock.cpp#L468) 
* 15867 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/sock.cpp#L485) Can't read certificate file
* 15868 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/net/sock.cpp#L490) Can't read key file


src/mongo/util/paths.h
----
* 13600 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/paths.h#L59) 
* 13646 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/paths.h#L88) stat() failed for file: " << path << " 
* 13650 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/paths.h#L116) Couldn't open directory '" << dir.string() << "' for flushing: 
* 13651 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/paths.h#L120) Couldn't fsync directory '" << dir.string() << "': 
* 13652 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/paths.h#L104) Couldn't find parent dir for file: 


src/mongo/util/processinfo_linux2.cpp
----
* 13538 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/processinfo_linux2.cpp#L48) 


src/mongo/util/text.cpp
----
* 13305 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/text.cpp#L132) could not convert string to long long
* 13306 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/text.cpp#L141) could not convert string to long long
* 13307 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/text.cpp#L127) cannot convert empty string to long long
* 13310 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/text.cpp#L145) could not convert string to long long
* 16091 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/text.cpp#L177) 


src/mongo/util/time_support.cpp
----
* 16226 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/time_support.cpp#L60) 
* 16227 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/time_support.cpp#L70) 
* 16228 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/time_support.cpp#L102) 


src/mongo/util/timer-posixclock-inl.h
----
* 16160 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/timer-posixclock-inl.h#L36) 


src/mongo/util/timer-win32-inl.h
----
* 16161 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/timer-win32-inl.h#L37) 


src/mongo/util/timer.cpp
----
* 16162 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/timer.cpp#L54) 
* 16163 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/timer.cpp#L55) 


src/mongo/util/touch_pages.cpp
----
* 16154 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/touch_pages.cpp#L45) namespace does not exist
* 16237 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/touch_pages.cpp#L75) readahead failed on fd 
* 16238 [code](http://github.com/mongodb/mongo/blob/master/src/mongo/util/touch_pages.cpp#L49) can't fetch extent file structure

