# ToBeGreen

### Description

ToBeGreen is a python3 library used for (de)serialization between python data objects and bytes strings. It is intended as a quick-implementation and prototyping tool for anyone who just needs to push data across a network between 2 python processes, while avoiding the following issues:
- Arbitrary code execution upon deserialization as in the default 'pickle' library and the extension 'dill' library
- Not being able to package binary objects or arbitrary objects as in the defualt 'json' library

### Naming Notes

This library used to be named 'Thwomp'. It is now named 'ToBeGreen' based upon a terrible pun in Spanish: the primary functions that this library provides are 'Ser', 'Ver', and 'Des' (for serialize, verify, and deserialize, respectively). Together, this would form the Spanish phrase 'Ser Verdes' (to be green).

### Copyright Information

See the file 'LICENSE.txt' for details.