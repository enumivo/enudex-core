# EnuDex Plugins

The enudex plugins are a collection of tools that brings new functionality without the need of modifications in the consensus and more sensitive areas of the enudex-core.

The main source of I/O of the enudex blockchain is the API. Plugins are a more powerful alternative to build more complex developments for when the current API is not enough.

Plugins are optional to run by node operator according to their needs. However, all plugins here will be compiled. 
# Available Plugins

Folder                             | Name                     | Description                                                                 | Category       | Status        | SpaceID     
-----------------------------------|--------------------------|-----------------------------------------------------------------------------|----------------|---------------|--------------|
[account_history](account_history) | Account History          | Save account history data                                                   | History        | Stable        | 4
[debug_witness](debug_witness)     | Debug Witness            | Run "what-if" tests                                                         | Debug          | Stable        |
[delayed_node](delayed_node)       | Delayed Node             | Avoid forks by running a several times confirmed and delayed blockchain     | Business       | Stable        |
[elasticsearch](elasticsearch)     | ElasticSearch Operations | Save account history data into elasticsearch database                       | History        | Experimental  | 6
[es_objects](es_objects)           | ElasticSearch Objects    | Save selected objects into elasticsearch database                           | History        | Experimental  |
[grouped_orders](grouped_orders)   | Grouped Orders           | Expose api to create a grouped order book of enudex markets              | Market data    | Experimental  |
[market_history](market_history)   | Market History           | Save market history data                                                    | Market data    | Stable        | 5
[snapshot](snapshot)               | Snapshot                 | Get a json of all objects in blockchain at a specificed time or block       | Debug          | Stable        | 
[witness](witness)                 | Witness                  | Generate and sign blocks                                                    | Block producer | Stable        | 
