このソフトウェアは、アプリケーションサーバの役割として、JBOSS バージョン１０上で稼働します。
データベースサーバはPostgeSQL バージョン9.4以上を使用します。
プログラム言語はJava 1.8以上を使用します。
以下の機能は、SinfoniaCloud　バージョン3と言う名称でリリースされます。

構成は、

1. アプリケーションサーバ
2. データベースサーバ
3. 並列分散処理サーバ
4. オブジェクトキャッシュサーバ
5. プロセス監視サーバ

の５つから構成されます。

主要な機能は、マルチサーバ上でマルチスレッドでJava　Objectを動作させ、並列処理を行うためのフレームワークです。オブジェクトをメモリ上にキャッシュし、データベースサーバへのアクセスを極力少なくするための機能を持っています。また、外部からの大量な要求をキューイングし並列処理要求をアプリケーションサーバに行います。アプリケーションサーバ上で動作するオブジェクトはトランザクションスコープがコミットすると、データベースサーバに自動的に永続化します。
複数のアプリケーションサーバのメモリ上のオブジェクトのバージョンの同期を自動的に管理するためにキャッシュサーバがこの機能を制御します。
更に、SinfoniaCloud上で動作するMDM（MasterData Management）と、そのMDM上で動作する日本語処理によるルールを記述したり、テストしたり、稼働させたりする日本語処理インタープリタの機能が搭載されています。
つまり、SinfoniaCloudというフレームワークと実際にアプリケーションを開発し稼働させる日本語処理環境の２つがOSSとして公開されています。





This software runs on JBOSS version 10 as an application server role.
The database server uses PostgeSQL version 9.4 or higher.
The programming language uses Java 1.8 or higher.
The following features are released under the name SinfoniaCloud version 3.
Configuration is

1. Application server
2. Database server
3. Parallel distributed processing server
4. Object cache server
5. Process monitoring server

It consists of five.
The main function is a framework for operating Java Objects in multiple threads on multiple servers and performing parallel processing. It has functions for caching objects in memory and minimizing access to the database server. It also queues a large number of external requests and makes parallel processing requests to the application server. Objects that run on the application server are automatically persisted to the database server when the transaction scope commits.
The cache server controls this feature to automatically manage the synchronization of versions of objects in the memory of multiple application servers.
Furthermore, MDM (Master Data Management) that runs on Sinfonia Cloud and the function of a Japanese-language processing interpreter that describes, tests, and runs rules based on Japanese-language processing that runs on the MDM are installed.
In other words, two frameworks called SinfoniaCloud and a Japanese processing environment that actually develops and runs applications are released as OSS.
