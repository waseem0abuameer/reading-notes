# File and stream I/O
File and stream I/O (input/output) refers to the transfer of data either to or from a storage medium.
In .NET, the System.IO namespaces contain types that enable reading and writing,

# Files and directories
You can use the types in the System.IO namespace to interact with files and directories. For example, you can get and set properties for files and directories, and retrieve collections of files and directories based on search criteria.

-------------------------------------------------------------------
# Here are some commonly used file and directory classes:
1. File 
2. FileInfo => helps create a FileStream object.
3. Directory 
4. DirectoryInfo 
5. Path 

----------------------------------------------------------------------------------
`````
See How to: Copy Directories, How to: Create a Directory Listing, and How to: Enumerate Directories and Files.
`````

---------------------------------------------------------------------------------------
# Streams

Streams involve three fundamental operations:
Reading - transferring data from a stream into a data structure, such as an array of bytes.
Writing - transferring data to a stream from a data source.
Seeking - querying and modifying the current position within a stream.

-----------------------------------------------------------------------------------------------

Here are some commonly used stream classes:
1. IsolatedStorageFileStream 
2. MemoryStream 
3. BufferedStream 
4. NetworkStream 
5. PipeStream 
6. CryptoStream 
7. FileStream

---------------------------------------------------------------------------------------------------------
# Readers and writers
The System.IO namespace also provides types for reading encoded characters from streams and writing them to streams. 

------------------------------------------------------------------------------------
# I/O and security
When you use the classes in the System.IO namespace, you must follow operating system security requirements such as access control lists (ACLs) to control access to files and directories. This requirement is in addition to any FileIOPermission requirements. You can manage ACLs programmatically. For more information, see How to: Add or Remove Access Control List Entries.


