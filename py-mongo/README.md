# Py-Mongo

An introduction, tutorial and collection of scripts for working with Py-Mongo.

***

## Installation

Before installing `Py-Mongo`, we first need to install `MongoDB`.

We can do this in Ubuntu by running the following command:

```bash
sudo apt-get install mongodb
```

By default, we will be unable to use the `MongoDB` packages we just installed. To be able to use them, we will have to run the following commands:

```bash
sudo rm -rf /var/lib/mongodb/mongod.lock
```

Then we reset for our changes to take effect:

```bash
sudo mongod --repair
```

After which we restart the service:

```bash
sudo service mongodb start
```

We can check the status of the database:

```bash
sudo service mongodb status
```

We then proceed to install `pip`:

```bash
sudo apt-get install python-pip
```

And then install `Py-Mongo`:

```bash
pip install pymongo
```

***
