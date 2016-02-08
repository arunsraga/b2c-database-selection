#### [back](getting_started_main.md)


Installing Cassandra is easy and you can follow the below steps to install it in most of the operating systems :


1- Download the Cassandra distribution binaries from the [download page](http://cassandra.apache.org/download/).

2- Use the below terminal command to extract the downloaded compressed file:

````
tar -xvzf datastax-ddc-version_number-bin.tar.gz

````

3-  Now Cassandra is ready to use, you can either use default configuration or change the configuration file from the below path:


````
cd datastax-ddc-version_number/conf

````

4- Run Cassandra using below terminal command:

````
bin/cassandra
````


If you are using linux-based systems, then you can also use some package managers to install cassandra such as Yum or apt-get as shown below:

Using apt-get, you need first to add the Cassandra distribution repository to the /etc/apt/sources.list.d/cassandra.sources.list by using the below terminal command:

````
echo "deb http://debian.datastax.com/datastax-ddc 3.version_number main" | sudo tee -a /etc/apt/sources.list.d/cassandra.sources.list
Then you can use below terminal commands to install Cassandra:

````
sudo apt-get update

sudo apt-get install datastax-ddc
````

In a similar way, you can install Cassandra using Yum package manager by first adding the  Cassandra distribution repository to the /etc/yum.repos.d/datastax.repo by using below terminal command:

````
[datastax-ddc]
````

Then you can easily install it by using below terminal command:

````
sudo yum install datastax-ddc
````