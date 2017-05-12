# Event Streams
The event stream definition defines the event stream schema. An event stream definition contains a unique name and a set of attributes assigned specific types, with uniquely identifiable names within the stream.

## Purpose
To define the schema based on which events are selected to be processed in the execution plan to which the event stream is attached.

## Syntax
The following is the syntax of a query that defines a new event stream.

	define stream <stream name> (<attribute name> <attribute type>, <attribute name> <attribute type>, ... );
  
### Paramaters
|Parameter                                  |Description    |
| -------------                             |:-------------:|
| `stream name`                             | The name of the event stream to be created. | 
|  `<attribute name> <attribute type>`      | The schema of an event stream is defined by adding the name and the type of each attribute as a value pair.
attribute name: A unique name for the attribute.
attribute type: The data type of the attribute value. This can be STRING, INT, LONG, DOUBLE, FLOAT or BOOLEAN.      |
 
