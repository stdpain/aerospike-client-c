## Examples 
Example shows the simple usage of Aerospike Node.js API.

To demonstrate Buffer datatype usage, examples use node.js msgpack 
package. To install msgpack,
	
	$sudo npm install -g msgpack.

To run the examples, 
	
	$node <file_name>

The following are the examples available:
	
put.js
get.js
batch_get.js
select.js
remove.js
operate.js
info.js

The config parameters to run the examples are given through
config.json file. The following config informations are necessary for the
examples to run.

	host : Server hostname (default : localhost)
	port : Server port (default : 3000)
	namespace : Namespace (default : test)
	set : Set name (default : demo)
	NoOfOps : Number of operations to be performed(default : 1000)

To load some sample data in the server run
	
	$node put.js

Having loaded the sample data, execute any of the examples to check 
the functionality.

All the example outputs the time it takes to complete 14000 operation.

Example Usage
	
	$node put.js	// Running put.js outputs the following
	14000 put: 3289ms

