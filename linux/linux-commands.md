### Using find

`find -name *txt`

### Shell Operators

`&` -> Allows you to run commands in the background

`&&` -> This allows you to combine multiple commands in one line

`>` -> This takes the out put of command before it and transfers to command after it

`>>` -> It appends

### Determining File Type

`file` -> Helps you determine the type of file

### Switching Between User

`-l or --login` -> This attribute to `su` drops you in the user's shell along with all the environment variables that you would want to access

### Common Directories

`/etc`	-> Stores system files used by OS like sudoers, passwd, shadow
`/var`	-> Stores data that is freequently access or used to store info by applications like /var/log
`/root`	-> The home for the root system user
`/tmp`	-> Volatile directory the contents of which are erased everytime the system reboots

### Python Web Server

Most machines now come with python3. A quick and easy way to share your files is to start a web server and start sharing your files that way.

`python3 -m http.server`

Once the server is up you can fetch files from the server by running wget in the remote machine.

`wget http://127.0.0.1:8000/file`

